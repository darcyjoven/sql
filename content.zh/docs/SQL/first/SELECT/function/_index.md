---
weight: 40
title: 常用函数
---

# 常用函数

## 数字

### 绝对值

```sql
select abs(-12) from dual;
select abs(12) from dual;
```

### 取整

```sql
-- 大于该数的最小整数
select ceil(20.2) from dual;
-- 小于该数的最大整数
select floor(20.2) from dual;
```

### 四舍五入

```sql
select round(20.679,2) from dual
```

### 求余数

```sql
select mod(10,3) from dual
```

### 截取部分值

```sql
select trunc(20.9987,3) from dual
```

## 字符串

### 拼接

```sql
select 'hello'||' world'||'!' from dual;
```

### 大小写

```sql
select lower('Hello') from dual;
select upper('Hello') from dual;
```

### 替换

```sql
select replace('hello,darcy','darcy','joven')from dual;
```

### 去空格

```sql
select 'hi,'||rtrim(' hello   ')||'joven' from dual;
select 'hi,'||ltrim(' hello   ')||'joven' from dual;
select 'hi,'||trim(' hello   ')||'joven' from dual;
```

### 截取部分字符串

```sql
select substr('hello world',8,2) from dual;
```

## 日期

### 当前时间

```sql
select current_date,sysdate from dual;
```

### 最近日期

```sql
select round(sysdate,'yyyy'),round(sysdate,'mm'),round(sysdate,'dd'),round(sysdate,'hh') from dual;
```

### 截取日期

```sql
select trunc(sysdate,'yyyy'),trunc(sysdate,'mm'),trunc(sysdate,'dd'),trunc(sysdate,'hh') from dual;
```

### 日期与字符串转换

```sql
select
to_char(sysdate,'yy/mm/dd hh:mi:ss'),
to_date('231017','yymmdd')
from dual
```

### 日期计算

```sql
select sysdate-1, sysdate + 1/24/2 from dual
```
