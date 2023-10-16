---
weight: 20
title: 聚合查询
---

# 聚合查询

聚合查询是一个比较特殊的查询，它不返回数据，而是返回一个聚合结果，比如求和、平均值、最大值、最小值等。

数据准备:

```sql
CREATE TABLE sales(
  location varchar2(10),
  product varchar2(10),
  price number(3),
  sold_at date
);

INSERT INTO sales(location, product, price, sold_at) VALUES('HQ', 'Coffee', 2, sysdate);
INSERT INTO sales(location, product, price, sold_at) VALUES('HQ', 'Coffee', 2, sysdate-1);
INSERT INTO sales(location, product, price, sold_at) VALUES('Downtown', 'Bagel', 3, sysdate-3);
INSERT INTO sales(location, product, price, sold_at) VALUES('Downtown', 'Coffee', 2, sysdate-2);
INSERT INTO sales(location, product, price, sold_at) VALUES('HQ', 'Bagel', 2, sysdate-2);
INSERT INTO sales(location, product, price, sold_at) VALUES('1st Street', 'Bagel', 3, sysdate-1);
INSERT INTO sales(location, product, price, sold_at) VALUES('1st Street', 'Coffee', 2, sysdate-1);
INSERT INTO sales(location, product, price, sold_at) VALUES('HQ', 'Bagel', 3, sysdate-5);
```

## GROUP-BY

> `GROUP BY`位置紧跟`WHERE`条件之后

GROUP-BY 是聚合函数的核心，`SELECT`的查询结果会依据`GROUP BY`字段进行汇总。

```sql
SELECT location
FROM sales
GROUP BY location;
```

    LOCATION
    ----------
    HQ
    Downtown
    1st Street

试一下以下查询：

```sql
SELECT
  location,
  product
FROM sales
GROUP BY location;
```

## 聚合函数

+ sum() 合计
+ count() 计数
+ avg() 平均值
+ max() 最大值
+ min() 最小值

```sql
SELECT
  location,
  COUNT(*) AS number_of_sales
FROM sales
GROUP BY location;
```

    LOCATION   NUMBER_OF_SALES
    ---------- ---------------
    HQ                       4
    Downtown                 2
    1st Street               2


```sql
SELECT
  location，
  sold_at,
  COUNT(*) AS sales_per_day
FROM sales
GROUP BY location,sold_at
ORDER BY location,sold_at;
```

    LOCATION   SOLD_AT     SALES_PER_DAY
    ---------- ----------- -------------
    1st Street 2023-10-15              2
    Downtown   2023-10-13              1
    Downtown   2023-10-14              1
    HQ         2023-10-11              1
    HQ         2023-10-14              1
    HQ         2023-10-15              1
    HQ         2023-10-16              1

## HAVING

> 紧跟`GROUP BY` 

在聚合的基础上进行筛选。


```sql
SELECT
  location，
  sold_at,
  COUNT(*) AS sales_per_day
FROM sales
GROUP BY location,sold_at
HAVING COUNT(*) = 1
ORDER BY location,sold_at;
```

    LOCATION   SOLD_AT     SALES_PER_DAY
    ---------- ----------- -------------
    Downtown   2023-10-13              1
    Downtown   2023-10-14              1
    HQ         2023-10-11              1
    HQ         2023-10-14              1
    HQ         2023-10-15              1
    HQ         2023-10-16              1


## 隐式聚合

```sql
select count(*) from sales;
```

    COUNT(*)
    ----------
            8

## 总结

SELECT 中关键字顺序：

1. SELECT 必须
2. FROM 必须
3. JOIN
4. WHERE
5. GROUP BY
6. HAVING
7. ORDER BY