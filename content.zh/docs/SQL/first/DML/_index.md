---
weight: 20
title: DML--数据操作语言
---

# DML--数据操作语言

## 新增

已知表student结构如下:
```sql
create table student(
    id number(10),
    name varchar(20),
    sex varchar(20),
    age number(5),
    birthday date
)
```

```sql
insert into student values(1,'张三','男',19,to_date('951221','yymmdd'));
insert into student (name,id,age) values('小红',2,19);
```

## 修改

            ID NAME                 SEX                     AGE BIRTHDAY
    ----------- -------------------- -------------------- ------ -----------
            1 张三                 男                       19 2095-12-21
            2 小红                                          19 

student资料如上

```sql
-- 1.更新小红性别为女
update student set sex='女' where name='小红';
-- 2.将所有人年龄更新为12
update student set age=12;
```

## 删除

            ID NAME                 SEX                     AGE BIRTHDAY
    ----------- -------------------- -------------------- ------ -----------
            1 张三                 男                       12 2095-12-21
            2 小红                 女                       12 

student资料如上

```sql
-- 1. 删除所有性别为男资料
delete from student where sex='男';
-- 2. 删除所有资料
delete from student;
```


> `update`和`delete`使用到了`where`语句，我们在`select`中会详细介绍和使用。