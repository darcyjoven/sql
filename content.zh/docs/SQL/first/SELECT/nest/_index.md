---
weight: 30
title: 嵌套查询
---

# 嵌套查询

资料准备：

```sql
CREATE TABLE CUSTOMERS (
   ID number(2),
   NAME VARCHAR2(8),
   AGE number(3),
   ADDRESS VARCHAR2 (10),
   SALARY number (10, 2)
);

INSERT INTO CUSTOMERS VALUES (1, 'Ramesh', 32, 'Ahmedabad', 2000.00);
INSERT INTO CUSTOMERS VALUES (2, 'Khilan', 25, 'Delhi', 1500.00);
INSERT INTO CUSTOMERS VALUES (3, 'Kaushik', 23, 'Kota', 2000.00);
INSERT INTO CUSTOMERS VALUES (4, 'Chaitali', 25, 'Mumbai', 6500.00);
INSERT INTO CUSTOMERS VALUES (5, 'Hardik', 27, 'Bhopal', 8500.00);
INSERT INTO CUSTOMERS VALUES (6, 'Komal', 22, 'Hyderabad', 4500.00);
INSERT INTO CUSTOMERS VALUES (7, 'Muffy', 24, 'Indore', 10000.00);
```

## 作为结果-SELECT

作为查询结果字段，这个时候要保证每次查询结果只有一个值。

查询每个人的薪水和最高薪水的差异金额

```sql
select a.name,a.salary,a.salary-(select max(b.salary) from customers b) salary_diff
from customers a;
```

    NAME           SALARY SALARY_DIFF
    -------- ------------ -----------
    Ramesh        2000.00       -8000
    Khilan        1500.00       -8500
    Kaushik       2000.00       -8000
    Chaitali      6500.00       -3500
    Hardik        8500.00       -1500
    Komal         4500.00       -5500
    Muffy        10000.00           0

## 作为条件-WHERE

### in

查询工资不是最高也不是最低的人

```sql
select name,salary from customers
where salary not in (
    (select max(salary) from customers),
    (select min(salary) from customers)
);
```

    NAME           SALARY
    -------- ------------
    Ramesh        2000.00
    Kaushik       2000.00
    Chaitali      6500.00
    Hardik        8500.00
    Komal         4500.00

`in`除了查询单个值，还可以作为范围条件。

```sql
select name,salary from customers
where salary in (select salary from customers where salary > 4000);
```

> 和`in` 一样，这里可以是多字段

以上查询，查询薪水大于 4000 的人，当然有更简单的方式写，这里知识演示用法。

    NAME           SALARY
    -------- ------------
    Chaitali      6500.00
    Hardik        8500.00
    Komal         4500.00
    Muffy        10000.00

### exists

`exists`和`in`可以互相转化，查询工资不是最高也不是最低的人改为`exists`写为：

```sql
select a.name,a.salary from customers a
where not exists (select max(b.salary) from customers b having max(b.salary)=a.salary)
and not exists (select min(b.salary) from customers b having max(b.salary)=a.salary);
```

    NAME           SALARY
    -------- ------------
    Ramesh        2000.00
    Khilan        1500.00
    Kaushik       2000.00
    Chaitali      6500.00
    Hardik        8500.00
    Komal         4500.00

### 作为字段

和`SELECT`一样，在`WHERE`查询条件中，也可以将子查询作为查询条件，这个时候要保证查询结果只有一个值。

同样是查询工资不是最高也不是最低的人

```sql
select name,salary from customers
where salary < (select max(salary) from customers)
and salary > (select min(salary) from customers);
```

    NAME           SALARY
    -------- ------------
    Ramesh        2000.00
    Kaushik       2000.00
    Chaitali      6500.00
    Hardik        8500.00
    Komal         4500.00

## 作为来源-FROM

查询结果可以当作一个表使用，即可以作为`FROM`和`JOIN`的来源。这个时候要保证，列名不重复（因为表的列名不重复）。

查询工资最高的人的姓名和地址

```sql
select a.name,a.address,a.salary from customers a,(select max(salary) salary from customers) b
where a.salary=b.salary;
```

    NAME     ADDRESS          SALARY
    -------- ---------- ------------
    Muffy    Indore         10000.00

## 总结

+ 查询结果为多笔时，可用在`FROM`、`JOIN`、`IN`、`EXISTS`

+ 查询结果为单笔，可以当作字段、单个值使用

