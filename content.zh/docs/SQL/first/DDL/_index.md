---
# bookCollapseSection: true
weight: 10
title: DDL--数据定义言
---

# DDL--数据定义语言

- 数据通过表存在数据库中
- 不区分大小写
- 表中规定每列的数据名称和数据类型
- 表结构影响后续数据的存储和检索

## 建立表

```sql
create student(
    name  varchar2(100),
    age   number(5),
    score number(4,2),
    birthday date
)
```

以上代码运行后创建了一个名称 student 的表，其中

- studnet 表名，在有同一个用户中，不能重名，需要满足标识符要求
- name 列名，在同一个表中，不能重名，需要满足标识符要求
- varchar2(100) 数据类型

### oracle 数据类型

- date 日期
- number() 数字类型 number(5) 为 5 位的小数 number(5,2) 位 5 位，有 2 位小数
- ~~blob/clob 二进制大数据~~
- varchar2(100) 长度为 100 的字符串
- timestamp 时间戳 （精确到 10 位的秒）

### 修改表

已有表的修改，请注意已有资料的情况

#### 增加字段

> 无论什么情况，都可以增加字段

```sql
alter table student add (
    class varchar2(20),
    parent varchar2(20)
)
```

以上在 student 中增加了两个字段

#### 减少字段

> 如果要减少的字段有任意一笔不为空的资料，不允许删除字段，所以删除字段前，需要先清空字段资料

[UPDATE语法](../DML/#修改)

```sql
update student set parent = null;
alter table student drop column parent;
```

1. 更新字段值为`null`
2. 删除字段

#### 修改字段

> 修改字段无论是数据类型，还是字段名称，如果已有资料也无法修改

##### 通过删除字段

[UPDATE语法](../DML/#修改)

1. 新建临时字段存储要修改列的值
2. 将旧字段值设置为 null 后删除
3. 新增要新增的列
4. 新列的值设置为临时字段
5. 删除临时字段

> 此方式，最后修改的字段总是在最后

```sql
alter table student add name2 varchar(100);
update student set name2 = name;
update student set name = null;
alter table student drop column name;
alter table student add id varchar2(100);
update student set id = name2;
update student set name2 = null;
alter table student drop column name2;
```

##### 通过重建表

<!-- TODO链接到update select -->
[UPDATE语法](../DML/#修改)

1. 新建临时表存储现表资料
2. 删除现表
3. 重建建立表
4. 将临时表资料储存到新表
5. 删除临时表

> 此方式，字段的顺序可以受到控制

```sql
create table student2 as select * from student;
drop table student;
create table student (
    id  varchar2(100),
    age   number(5),
    score number(4,2),
    birthday date
);
insert into student select * from student2;
drop table student2;
```

## 删除表

> 删除表比较简单，但要注意备份资料

```sql
drop table student;
```

## 主键

将一个或多个字段设置为主键，可以保证资料不重复。

> 一个表最多存在 1 个主键，可以没有主键。主键名和表名一样，在用户中不可重复。

例如：身份证，ID 号这些不重复的字段。如果是班级的话，xx 届和 xx 班，两字段加在一起这样也是不重复的。

### 创建表时创建主键

```sql
create table student (
    id  varchar2(100),
    age   number(5),
    score number(4,2),
    birthday date,
    constraint student_pk primary key(id)
)
```

### 创建表后创建主键

```sql
create table student (
    id  varchar2(100),
    age   number(5),
    score number(4,2),
    birthday date
);
alter table student add constraint student_pk primary key (id);
```

## 索引

> 索引在表中相当于时目录，如果查询时，走索引速度提升很多。（只在巨量数据时有明显效果，数据库量不多时，没必要考虑索引）

- 查询通过索引可以提高查询速度，但会降低增删改的速度
- 一个表可以建立多个索引
- 只有数据量多的时候索引才会明显提升查询速度
- 只有合适的查询（SELECT）语句才能使用索引查询

### 创建索引

```sql
create index student_idx on student(id,age);
```

### 删除索引

```sql
drop index student_idx;
```

### 重建索引

> 删除重新创建即可

```sql
drop index student_idx;
create index student_idx on student(id,age);
```

## ~~外键~~

当a表c1字段必须时b表d1字段中的一个的时候，可以将c1设置为d1字段的外键。这样在新增a表资料时，c1字段会自动检查是否在b表中存在，不存在不允许新增该资料。


> 创建外键，会时两个表耦合性增加，且不利于问题排查，所以不建议使用，了解有这个东西即可。这个检查可以通过代码实现。

### 创建

1. 创建表时创建
```sql
create table class (
    id  number(10)
);
create table student(
    id number(10),
    class number(10)
    constraint student_fk
        foreign key (class)
        references class (id)
);
```
2. 创建表后创建
```sql
create table class (
    id  number(10)
);
create table student(
    id number(10),
    class number(10)
);
alter table student
add constraint student_fk
   foreign key (class)
   references class (id);
```

### 删除

```sql
alter table  student drop constraint student_fk
```

### 重建

删除后重新添加即可

