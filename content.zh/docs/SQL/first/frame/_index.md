---
# bookCollapseSection: true
weight: 9
title: ORACLE数据库结构
---

# ORACLE 数据库结构

## 物理结构-表空间

### TABLEPACE--表空间

数据库存储数据的物理文件，所有数据库的表资料都储存在不同的表空间中。

```sql
SQL> SELECT TABLESPACE_NAME,
  2           STATUS,
  3           CONTENTS,
  4           LOGGING
  5      FROM DBA_TABLESPACES;

TABLESPACE_NAME                STATUS    CONTENTS  LOGGING
------------------------------ --------- --------- ---------
SYSTEM                         ONLINE    PERMANENT LOGGING
SYSAUX                         ONLINE    PERMANENT LOGGING
UNDOTBS1                       ONLINE    UNDO      LOGGING
TEMP                           ONLINE    TEMPORARY NOLOGGING
USERS                          ONLINE    PERMANENT LOGGING
DBS1                           ONLINE    PERMANENT LOGGING
TEMPTABS                       ONLINE    PERMANENT LOGGING
RPTDBS1                        ONLINE    PERMANENT LOGGING
BLOBDBS1                       ONLINE    PERMANENT LOGGING
```

### 表空间文件

表空间是表空间文件组成，表空间文件在建立时就定义了大小，当表空间文件满时，需要增加表空间文件。已建立表空间文件不能删除，移动，变小。

```sql
SQL> SELECT TABLESPACE_NAME,
  2           'PERMANENT' TABLESPACE_KIND,
  3           FILE_NAME,
  4           STATUS,
  5           AUTOEXTENSIBLE,
  6           BYTES/1024/1024 CURR_BYTES_M,
  7           ONLINE_STATUS
  8      FROM DBA_DATA_FILES --永久表空间（含撤销表空间）
  9     UNION ALL
 10    SELECT TABLESPACE_NAME,
 11           'TEMPORARY' TABLESPACE_KIND,
 12           FILE_NAME,
 13           STATUS,
 14           AUTOEXTENSIBLE,
 15           BYTES/1024/1024 CURR_BYTES_M,
 16           'ONLINE' ONLINE_STATUS
 17      FROM DBA_TEMP_FILES;

TABLESPACE_NAME                TABLESPACE_KIND FILE_NAME                                                                        STATUS    AUTOEXTENSIBLE CURR_BYTES_M ONLINE_STATUS
------------------------------ --------------- -------------------------------------------------------------------------------- --------- -------------- ------------ -------------
SYSTEM                         PERMANENT       /u2/oracle/oradata/topprod/system01.dbf                                          AVAILABLE YES                   32750 SYSTEM
SYSAUX                         PERMANENT       /u2/oracle/oradata/topprod/sysaux01.dbf                                          AVAILABLE YES                    1030 ONLINE
UNDOTBS1                       PERMANENT       /u2/oracle/oradata/topprod/undotbs01.dbf                                         AVAILABLE YES            32767.984375 ONLINE
USERS                          PERMANENT       /u2/oracle/oradata/topprod/users01.dbf                                           AVAILABLE YES                 6466.25 ONLINE
DBS1                           PERMANENT       /u2/oracle/oradata/topprod/dbs1-01.dbf                                           AVAILABLE NO                     2000 ONLINE
```

> 表空间满了之后，需要增加表空间文件，任何表空间的操作都需要管理员账号登陆


## 逻辑结构

1. SID -- 库

`库`为数据库的第一层结构，GP5.3中库名对应`区`。

如`topprod`对应ERP正式区，`toptest`对应ERP测试区。

不同库之间不能直接访问，需要通过网络访问。

2. user -- 用户

用户是库之下的第二层结构，在GP5.3中用户对应的是营运据点

如`forewin`对应的就是`forewin`这个营运据点。

不同用户之间资料，可以通过赋予权限访问。

3. 第三次结构：table、view、index...

存储数据的基本单元表--`table`，以及索引、视图、触发器等，都属于一个用户。
也就是这些数据结构都建立并储存在用户下面。

