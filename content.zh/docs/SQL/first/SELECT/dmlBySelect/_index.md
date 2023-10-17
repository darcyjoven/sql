---
weight: 60
title: 使用SELECT更新数据
---

# 使用SELECT更新数据


## 新增数据-INSERT

在`insert`语句中除了使用`values()`还可以使用`select`，且查询结果可以是多笔。

```sql
insert into student (id,name) select id,name from student2;
```

## 创建表-CREATE

和创建视图一样，通过`SELECT`还可以创建table

```sql
create table student3 as select id,name from student2;
```

