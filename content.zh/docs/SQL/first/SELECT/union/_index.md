---
weight: 49
title: 查询结果操作
---

## UNION

查询结果合并，会将union两侧的查询结果合并显示，是结果合并，而不是多表查询中的列和结果都合并

```sql
select 1,2,3 from dual
union
select 2,3,4 from dual
union
select 1,2,3 from dual;
```
             1          2          3
    ---------- ---------- ----------
            1          2          3
            2          3          4

> dual 是一个只一列，且只有一行资料的ORACLE初始化时已经建立好的表，且资料不允许更新，修改，删除

查询结果操作对查询语句有要求：

+ 列的数量和顺序必须一致
+ 列的数据类型必须一致

查询后的结果，列名已第一个SQL字段名

UNION还支持`UNION ALL`语法，此语法不会去掉重复资料

```sql
select 1,2,3 from dual
union
select 2,3,4 from dual
union all
select 1,2,3 from dual;
```
             1          2          3
    ---------- ---------- ----------
            1          2          3
            2          3          4
            1          2          3


## ~~MINUS~~

MINUS 查询结果是两个查询结果的差集，即在第一个查询结果中存在，但是不在第二个查询结果中的数据

```sql
(select 1,2,3 from dual
union
select 2,3,4 from dual)
minus
select 1,2,3 from dual;
```

             1          2          3
    ---------- ---------- ----------
            2          3          4


## ~~INTERSECT~~

INTERSECT 查询结果是两个查询结果的交集，即在两个查询结果中都存在的数据

```sql
(select 1,2,3 from dual
union
select 2,3,4 from dual)
INTERSECT
select 1,2,3 from dual;
```

            1          2          3
    ---------- ---------- ----------
            1          2          3


## rownum 字段

1. rownum：伪列。顾名思义：是数据库自己创建出来的字段。
2. rownum是个伪列，伴随着结果集的过程而生成的字段。

```sql
select id,user_name,over,rownum
from user1;
```

        ID USER_NAME  OVER           ROWNUM
        ---- ---------- ---------- ----------
        1 tangseng   dtgdf               1
        2 sunwukong  dzsf                2
        1 zhubajie   jtsz                3
        1 shaseng    jslh                4

+ 对查询结果进行依次编号

```sql
  ID USER_NAME  OVER           ROWNUM
---- ---------- ---------- ----------
   1 tangseng   dtgdf               1
   1 shaseng    jslh                4
   1 zhubajie   jtsz                3
   2 sunwukong  dzsf                2
```

+ rownum 编号运行在order by之前，所以编号会导致rownum也重新排序

```sql
select id,user_name,over,rownum from (
select id,user_name,over
from user1 order by id);
```

        ID USER_NAME  OVER           ROWNUM
        ---- ---------- ---------- ----------
        1 tangseng   dtgdf               1
        1 shaseng    jslh                2
        1 zhubajie   jtsz                3
        2 sunwukong  dzsf                4

+ 若像依据ID对rownum编号，需要使用嵌套查询，先排序，将排序号的资料重新增加rownum

```sql
select id,user_name,over,rownum2,rownum from (
select id,user_name,over,rownum rownum2
from user1 order by id);
```

        ID USER_NAME  OVER          ROWNUM2     ROWNUM
        ---- ---------- ---------- ---------- ----------
        1 tangseng   dtgdf               1          1
        1 shaseng    jslh                4          2
        1 zhubajie   jtsz                3          3
        2 sunwukong  dzsf                2          4
+ 注意子查询中的rownum使用后编号就依据固定下来了，其它查询使用子查询中的rownum，不会随着排序而改变

> rownum经常用来进行筛选只要查询结果的某些列

+ 查询结果的前3笔

```sql
select * from user1
where rownum <=3;
```

+ 查询结果的第2，3笔 -- 这里必须使用嵌套查询，先将rownum固定下来，然后才能选取第2笔和第3笔

错误写法

~~`select * from user1 where rownum between 2 and 3;`~~

正确写法
```sql
select * from (
select user1.*,rownum rownum2 from user1)
where rownum2 between 2 and 3;
```

+ 查询第2笔之后的笔数
```sql
select * from (
select user1.*,rownum rownum2 from user1)
where rownum2 > 2;
```