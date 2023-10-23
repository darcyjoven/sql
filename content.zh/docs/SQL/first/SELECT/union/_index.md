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