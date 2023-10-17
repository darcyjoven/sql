---
weight: 50
title: 视图
---

# 视图

视图-VIEW是通过查询结果建立的一个对象

+ 视图必须通过查询结果建立，列名不可重复
+ 视图不储存数据，数据仍在原表
+ 视图每次查询重新查询资料

## 建立视图

```sql
create view stu_view as
select name,id form student
```

## 删除视图

```sql
drop view stu_view
```

## 重建视图

```sql
create or replace view stu_view as
select name,id form student
```