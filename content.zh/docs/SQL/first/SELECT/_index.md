---
bookCollapseSection: true
weight: 30
title: 查询语句详解
---

# SELECT--查询语句详解

## 查询语句组成

### 结果--字段（select）

> 查询语句的最前面

```sql
select 字段1,字段2,字段3,'6班' 班级
```

- `*` 匹配所有字段:

```sql
select *
select student.*,class.*
```

- 字面常量：
  数值和字符串都可以以字面常量作为字段结果

- 别名：

```sql
select id,name 姓名,age as 年纪
```

查询结果中会以别名显示

- 字段运算:

```sql
select id,'姓名'||name,age+2
```

查询字段可以进行字段运算，字符串拼接为`||`拼接，数学运算符号`+-*/`都可以使用

- 判断语句：
  SQL 中判断语句比较特殊，它只能返回一个值，且每个分支返回值必须一致。

```sql
-- 从一个变量的值判断
select case sex when '男' then '我是男生' when '女' then '我是女生' else '我是人妖' end as 性别
-- 从条件表达式判断
select case when age < 8 then '小学生' when age < 16 then '初中生' when age < 24 '大学生' else '老人' end as 年纪
```

### 来源--表（from）

> 必须在字段之后

```sql
from student,class
```

- 别名：

```sql
from student as s
```

- 表字段:

```sql
select s.id,class.id from student as s,class
```

当多个表中字段有重名时，使用字段必须指定字段属于哪个表

### 条件--判断语句（where）

> 必须放在 from 之后

```sql
where student.id > 1
and student.name like '张%'
and student.id=class.id
and (student.age > 18 or student.age < 10)
and student.birth between to_date('2000-01-01','yyyy-mm-dd') and to_date('2020-12-31','yyyy-mm-dd')
and sex in ('男','女')
```

> where 可以从众多的资料中筛选出符号目标要求的资料，所以 where 在查询语句中是最复杂的。

> 我们在写 where 语句的时候，应该从简单语句开始写，分块写，防止多个筛选条件混合到一起。

- 比较运算符：
  大于、小于、等于这些运算符在 where 中也可以写。

`>=`,`<=`,`<>/!=`

- 逻辑运算符：
  多个运算符之间用`and`或者`or`相连。 括号会改变判断语句运算顺序

```sql
-- 年纪大于10岁或者小于5岁的女人
where (age > 10 or age < 5) and sex ='女'
-- 年纪大于10岁的人或者小于5岁的女人
where age > 10 or (age < 5 and sex ='女')
```

- 模糊查询：
  字符串模糊查询，like 运算符，
  `%`匹配任意多(包括 0)个任意字符，
  `_`匹配一个任意字符

```sql
-- 匹配'张'开始的字符串   张三 张  张98ahs 等都符和
where name like '张%'
-- 匹配'张'开始，且后面之后一个字符的字符串  张三 张四 张w 符和  张 张sw  不符合
where name like '张_'
-- 匹配字符中有一个'h'和'o',且'h'在'o'前面， hello hsasaodaidup ooohhooo 都符和
where name like '%h%o'
```

- between 范围判断:

between 可以判断一个连续的区间，数值，日期，单个字符都可以判断。

> 这里的`and` 和上面的`and`不是同一个意思。

```sql
-- 年纪在1到10之间
where age between 1 and 10
```

- in 范围判断：
  in 判断一个值是否在某个范围之内，这个不是连续的，而是一个集合。

```sql
-- 年纪是1，2，10
where age in (1,2,10)
-- 年纪不是18，19
where age not in (18,19)
-- 可以是多个字段
where (name,age) in (('darcy',19),('joven',10))
```

### 顺序--排序（order-by）

> 在 sql 语句的最后一步写，不一定是 where 后

> 可以不排序，此时数据库按照查出来的顺序排序

```sql
order by name,age desc,id esc
```

- 多字段：
  排序是按照字段先后顺序排，如果第一个字段有相同，才会按照第二个字段排序，第二个也相同，才会按第三个...

- 顺序/倒叙:
  顺序是按照 ASCII 表中数字大小排序的，中文是按照 GBK 表中数字大小排序的（既不是笔画也不是拼音）。

`esc`是顺序，`desc`是倒叙，如果补标注默认是`esc`倒叙


