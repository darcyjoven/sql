---
title: "一篇文章学完SQL"
weight: 10
date: 2023-07-20T09:59:33+08:00
lastmod: 2023-07-20T09:59:33+08:00
tags: ["SQL"]
categories: ["SQL"]
# bookComments: false
# bookSearchExclude: false
---

# 一篇文章学完 SQL

## 前言 -- 教务处系统

紧急！！！`清华小学`现急需一个教务处管理系统，否则学生将毕业不了。

现在有一个 `oracle` 数据库系统，请协助`清华小学`开发一个教务处管理系统。

如果成功你将被`清华小学`保送`清华大学`！！！

## 第一天 人员管理

所有人都可以去食堂吃饭，都可以打水，进校园门。

我们为能进入学校的所有人建立一个表，表中有以下字段：

- 姓名
- 性别
- 出生日期
- 联系方式

我们在执行以下 SQL：

```sql
CREATE TABLE people(
    name VARCHAR2(40),
    sex number(1),
    birthday DATE,
    contact number(11)
);
COMMENT ON TABLE people IS '人员信息表';
COMMENT ON COLUMN people.name IS '姓名';
COMMENT ON COLUMN people.sex IS '性别，1.男 2.女';
COMMENT ON COLUMN people.birthday IS '出生日期';
COMMENT ON COLUMN people.contact IS '联系方式';
```

如果没有问题的话，请运行以下命令，查看已经建立的表：

```sql
DESC people;
```

你会发现，你建立的表的所以字段都转为大写了，这是因为 ORACLE 自动将表名/字段名称都转为大写：

```sql
Name     Type         Nullable Default Comments
-------- ------------ -------- ------- ----------
NAME     VARCHAR2(40) Y                姓名
SEX      NUMBER(1)    Y                性别，1.男 2.女
BIRTHDAY DATE         Y                出生日期
CONTACT  NUMBER(11)   Y                联系方式
```

等等，每个人都有居住地址，我们要邮寄时会用到，但是我们已经建立表了，怎么办？
不要紧，反正我们还没有录入人员资料，我们偷偷将表删掉，重新建立一个！😋

删掉原来表：

```sql
DROP TABLE people;
```

建立新的`people`表，新增一个`address`字段：

```sql
CREATE TABLE people(
    name VARCHAR2(40),
    sex number(1),
    birthday DATE,
    contact number(11),
    address VARCHAR2(255)
);
COMMENT ON TABLE people IS '人员信息表';
COMMENT ON COLUMN people.name IS '姓名';
COMMENT ON COLUMN people.sex IS '性别，1.男 2.女';
COMMENT ON COLUMN people.birthday IS '出生日期';
COMMENT ON COLUMN people.contact IS '联系方式';
COMMENT ON COLUMN people.address IS '地址';
```

哈哈，成功了，我们重新建了一个表

```sql
Name     Type          Nullable Default Comments
-------- ------------- -------- ------- ----------
NAME     VARCHAR2(40)  Y                姓名
SEX      NUMBER(1)     Y                性别，1.男 2.女
BIRTHDAY DATE          Y                出生日期
CONTACT  NUMBER(11)    Y                联系方式
ADDRESS  VARCHAR2(255) Y                地址
```

我们尝试录入一下小明，和小红两位同学：

```sql
INSERT INTO people VALUES('小明',1,to_date('1990-01-01','yyyy-mm-dd'),'13888888888','北京');
INSERT INTO people VALUES('小红',2,to_date('1990-01-01','yyyy-mm-dd'),'13999999999','上海');
```

我们再尝试查询一下，看看是否成功

```sql
SELECT * FROM people;

NAME                                     SEX BIRTHDAY         CONTACT ADDRESS
---------------------------------------- --- ----------- ------------ --------------------------------------------------------------------------------
小明                                       1 1990-01-01   13888888888 北京
小红                                       2 1990-01-01   13999999999 上海
```

**练习**

1. 请为`people`增加以下栏位：

| 字段      | 数据类型     | 备注       |
| :-------- | :----------- | :--------- |
| card_id   | varchar2(18) | 身份证号码 |
| join_date | date         | 入校日期   |

2. 增加后，新增以下人员的信息：

```sql
INSERT INTO people (name,sex,birthday,contact,address,card_id,join_date)
VALUES('小明',1,to_date('1990-01-01','yyyy-mm-dd'),'13888888888','北京','123456789012345001',to_date('2018-01-01','yyyy-mm-dd'));

INSERT INTO people (name,sex,birthday,contact,address,card_id,join_date)
VALUES('小红',2,to_date('1990-01-01','yyyy-mm-dd'),'13999999999','上海','123456789012345002',to_date('2018-01-01','yyyy-mm-dd'));

INSERT INTO people (name,sex,birthday,contact,address,card_id,join_date)
VALUES('刚子',1,to_date('1970-01-01','yyyy-mm-dd'),'13999999999','旅顺','123456789012345003',to_date('2018-01-01','yyyy-mm-dd'));

```

## 第二天 学生、老师与后勤

前一天我们完成了人员的录入，将学校内所有的人员建立一个统一存放的系统。但是每个人员的职责是不同的，我们需要需要有一张表来记录每人的特殊属性，例如：学生肯定有一个家长、老师有不同的薪水、保安负责不同的大门...

### 我们来建立以下表结构

**学生 students**
字段|数据类型|备注
:---|:-----|:-----
card_id|varchar2(18)|身份证号码
student_id|varchar2(18)|学号
parent|varchar2(18)|家长
parent_phone|varchar2(11)|家长电话
create_date|date|生效日期
delete_date|date|失效日期

**教师 teachers**
字段|数据类型|备注
:---|:-----|:-----
card_id|varchar2(18)|身份证号码
job_id|varchar2(18)|工号
salary|number(10,2)|薪水
course|varchar2(100)|负责课程
create_date|date|生效日期
delete_date|date|失效日期

**后勤 logistics**
字段|数据类型|备注
:---|:-----|:-----
card_id|varchar2(18)|身份证号码
job_id|varchar2(18)|工号
salary|number(10,2)|薪水
gate|varchar2(10)|负责大门
create_date|date|生效日期
delete_date|date|失效日期

{{< details title="提示" open=false >}}

```sql
create table students (
    card_id varchar2(18),
    student_id varchar2(18),
    parent varchar2(18),
    parent_phone varchar2(11),
    create_date date,
    delete_date date
);
create table teachers (
    card_id varchar2(18),
    job_id varchar2(18),
    salary number(10,2),
    course varchar2(100),
    create_date date,
    delete_date date
);
create table logistics (
    card_id varchar2(18),
    job_id varchar2(18),
    salary number(10,2),
    gate varchar2(10),
    create_date date,
    delete_date date
);
comment on table students is '学生';
comment on table teachers is '教师';
comment on table logistics is '后勤人员';
comment on column students.card_id is '学生卡号';
comment on column students.student_id is '学生学号';
comment on column students.parent is '家长';
comment on column students.parent_phone is '家长电话';
comment on column students.create_date is '创建时间';
comment on column students.delete_date is '删除时间';
comment on column teachers.card_id is '卡号';
comment on column teachers.job_id is '工号';
comment on column teachers.salary is '工资';
comment on column teachers.course is '课程';
comment on column teachers.create_date is '创建时间';
comment on column teachers.delete_date is '删除时间';
comment on column logistics.card_id is '卡号';
comment on column logistics.job_id is '工号';
comment on column logistics.create_date is '创建时间';
comment on column logistics.delete_date is '删除时间';



```

{{< /details >}}

请根据前一天的`CREATE TABLE`语法自己创建上面 3 张表，如果创建后要修改，请`DROP TABLE`后重新创建。

### 为两位同学登记，并登记一位老师

```sql
insert into students (card_id,student_id,parent,parent_phone,create_date,delete_date)
values ('123456789012345001', '080823', '大明', '13888888888', sysdate, null);
insert into students (card_id,student_id,parent,parent_phone,create_date,delete_date)
values ('123456789012345002', '080824', '大红', '13988888888', sysdate, null);
insert into teachers (card_id,job_id,salary,course,create_date,delete_date)
values ('123456789012345003', '070813', 3456, '思想与道德2004版', sysdate, null);
```

{{< hint danger >}}
**紧急**

刚刚接到上级通知，《思想与道德 2004 版》，从之后升级为《思想与道德 2007 版》。
{{</ hint >}}

天哪，我又得把所有的《思想与道德 2004 版》的老师修改为《思想与道德 2007 版》了，幸亏现在只等级了一位老师。

我们直接运行下面 sql，执行更新：

```sql
-- 更新
update teachers set course = '思想与道德2007版';
-- 查看更新后的老师信息
select * from teachers;
-- 查询结果
CARD_ID            JOB_ID                   SALARY COURSE                                                                           CREATE_DATE DELETE_DATE
------------------ ------------------ ------------ -------------------------------------------------------------------------------- ----------- -----------
123456789012345003 070813                  3456.00 思想与道德2007版                                                                  2023-08-03
```

> 😎😎😎 我们又解决了一个问题！

### 登记更多老师

我们来继续登记老师，这次我们将学校的老师都登陆进去。登记之前我们去问下校长有哪些课程又能还要更新，防止我们后面还要重新修改。

    你：校长请问有哪些课程要更新吗？
    校长：这个不知道呀，你去问刚子吧。
    你：刚子老师，我们有哪些课程要更新吗？
    刚子：这个我们也不知道呀，都是接到上面通知就更新了，不确定呢，也许后面还要改语文和数学。
    你：好的。😨

> 这可怎么办呢？总不能之后每个课调整都要每个老师的课都修改一下吧。我们需要一个好办法！

💡💡💡 我们只要将课程放在一张表上，每次我们只要更新这个表一条数据的课程名称，老师只要关联到指定的课程就行！

1. 我们先将原来的 teachers 中的`course`改为`course_id`，并将数据类型修改为`number(5)`。

```sql
alter table teachers rename column course to course_id;
alter table teachers modify course_id number(5);
```

呀，报错了。

```
ORA-01439: column to be modified must be empty to change datatype
```

{{< hint danger >}}
**注意**
只有字段的值是空的才能更新字段的类型，如果修改已有资料的字段，请先更新为空然后再修改字段数据类型。

更新时请先备份保存。
{{</ hint >}}

我们需要先将字段`course_id`字段更新为空，再进行处理。

```sql
update teachers set course_id = null;
alter table teachers modify course_id number(5);
```

> 😎😎😎 瞧，我们刚刚解决了一个数据库报错！

2. 我们再新增一个表`courses`

**课程 courses**

| 字段        | 数据类型      | 说明     |
| :---------- | :------------ | :------- |
| course_id   | number(5)     | 课程编码 |
| name        | varchar2(100) | 课程名称 |
| create_date | date          | 生效时间 |
| delete_date | date          | 失效时间 |

{{< details title="提示" open=false >}}

```sql
create table courses (
    course_id number(5),
    name varchar2(100),
    create_date date,
    delete_date date
);
comment on table  courses is '课程表';
comment on column courses.course_id is '课程编码';
comment on column courses.name is '课程名称';
comment on column courses.create_date is '生效时间';
comment on column courses.delete_date is '失效时间';
```

{{</ details >}}

3. 我们将所有课程一次性登记，并设置刚子老师的课程

sql 太长，请自己点开
{{< details title="提示" open=false >}}

```sql
insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (1, '语文1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (2, '数学1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (3, '英语1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (4, '道德与法治1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (5, '科学1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (6, '计算机基础1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (7, '体育1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (8, '音乐1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (9, '美术1', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (10, '语文2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (11, '数学2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (12, '英语2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (13, '道德与法治2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (14, '科学2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (15, '计算机基础2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (16, '体育2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (17, '音乐2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (18, '美术2', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (19, '语文3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (20, '数学3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (21, '英语3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (22, '道德与法治3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (23, '科学3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (24, '计算机基础3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (25, '体育3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (26, '音乐3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (27, '美术3', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (28, '语文4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (29, '数学4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (30, '英语4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (31, '道德与法治4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (32, '科学4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (33, '计算机基础4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (34, '体育4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (35, '音乐4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (36, '美术4', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (37, '语文5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (38, '数学5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (39, '英语5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (40, '道德与法治5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (41, '科学5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (42, '计算机基础5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (43, '体育5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (44, '音乐5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (45, '美术5', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (46, '语文6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (47, '数学6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (48, '英语6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (49, '道德与法治6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (50, '科学6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (51, '计算机基础6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (52, '体育6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (53, '音乐6', to_date('03-08-2023', 'dd-mm-yyyy'), null);

insert into courses (COURSE_ID, NAME, CREATE_DATE, DELETE_DATE)
values (54, '美术6', to_date('03-08-2023', 'dd-mm-yyyy'), null);
```

{{</ details >}}

刚子老师是教 3 年纪的道德与法治，我们设置为对应的 id`22`。

```sql
update teachers set course_id = 22;
```

后面如果要修改任意一门课程名称，只要修改`courses`对应的名称即可。

我们现在来增加更多老师的信息

因为插入资料较多，请点击此连接查看<a href="../attach/teachers-people" target="_blank">insert people&teachers</a>

插入前请确认表结构如下：

```sql
-- teachers
Name        Type         Nullable Default Comments
----------- ------------ -------- ------- --------
CARD_ID     VARCHAR2(18) Y                卡号
JOB_ID      VARCHAR2(18) Y                工号
SALARY      NUMBER(10,2) Y                工资
COURSE_ID   NUMBER(5)    Y                课程
CREATE_DATE DATE         Y                创建时间
DELETE_DATE DATE         Y                删除时间
-- people
Name      Type          Nullable Default Comments
--------- ------------- -------- ------- ----------
NAME      VARCHAR2(40)  Y                姓名
SEX       NUMBER(1)     Y                性别，1.男 2.女
BIRTHDAY  DATE          Y                出生日期
CONTACT   NUMBER(11)    Y                联系方式
ADDRESS   VARCHAR2(255) Y                地址
CARD_ID   VARCHAR2(18)  Y                身份证号码
JOIN_DATE DATE          Y                入校日期
```

让我们试一下用`join`来查看所有老师的姓名、薪水和对应的课程名称。

```sql
SELECT people.name,salary,courses.name FROM teachers
LEFT JOIN people ON teachers.card_id = people.card_id
LEFT JOIN courses ON courses.course_id = teachers.course_id;
```

瞧瞧，伙计，我们已经把老师的资料查出来。🤓🤓🤓

```
NAME                                           SALARY NAME
---------------------------------------- ------------ --------------------------------------------------------------------------------
赵富                                         10359.00 数学5
孙吏                                         11554.00 英语5
刘国                                          5884.00 道德与法治5
冯倝                                          4001.00 科学5
赵昴                                         10334.00 计算机基础5
赵莎                                         11174.00 体育5
吴星                                         11243.00 音乐5
孙洛                                          8474.00 美术5
魏冬                                         11587.00 语文6
杨晓                                          8170.00 数学6
沈玟                                         11260.00 英语6
```

这章结束你的表结构应该如下：

```sql
SQL> desc people;
Name      Type          Nullable Default Comments
--------- ------------- -------- ------- ----------
NAME      VARCHAR2(40)  Y                姓名
SEX       NUMBER(1)     Y                性别，1.男 2.女
BIRTHDAY  DATE          Y                出生日期
CONTACT   NUMBER(11)    Y                联系方式
ADDRESS   VARCHAR2(255) Y                地址
CARD_ID   VARCHAR2(18)  Y                身份证号码
JOIN_DATE DATE          Y                入校日期

SQL> desc teachers;
Name        Type         Nullable Default Comments
----------- ------------ -------- ------- --------
CARD_ID     VARCHAR2(18) Y                卡号
JOB_ID      VARCHAR2(18) Y                工号
SALARY      NUMBER(10,2) Y                工资
COURSE_ID   NUMBER(5)    Y                课程
CREATE_DATE DATE         Y                创建时间
DELETE_DATE DATE         Y                删除时间

SQL> desc students;
Name         Type         Nullable Default Comments
------------ ------------ -------- ------- --------
CARD_ID      VARCHAR2(18) Y                学生卡号
STUDENT_ID   VARCHAR2(18) Y                学生学号
PARENT       VARCHAR2(18) Y                家长
PARENT_PHONE VARCHAR2(11) Y                家长电话
CREATE_DATE  DATE         Y                创建时间
DELETE_DATE  DATE         Y                删除时间

SQL> desc logistics;
Name        Type         Nullable Default Comments
----------- ------------ -------- ------- --------
CARD_ID     VARCHAR2(18) Y                卡号
JOB_ID      VARCHAR2(18) Y                工号
SALARY      NUMBER(10,2) Y                薪水
GATE        VARCHAR2(10) Y                负责大门
CREATE_DATE DATE         Y                创建时间
DELETE_DATE DATE         Y                删除时间

SQL> desc courses;
Name        Type          Nullable Default Comments
----------- ------------- -------- ------- --------
COURSE_ID   NUMBER(5)     Y                课程编码
NAME        VARCHAR2(100) Y                课程名称
CREATE_DATE DATE          Y                生效时间
DELETE_DATE DATE          Y                失效时间
```

### 练习

查询一下每个老师的这些资料

| 姓名 | 薪水 | 入校时间 | 工号 |
| ---: | :--- | :------- | :--- |
| 刚子 | 3... | 2008...  | 7... |

## 第三天 班级系统

上一节课，我们建立了非常牛逼的教师管理系统，登记老师之后，我们随时可以查询老师的任何信息。
如果要改课程的名称也很容易。

今天我们继续完善一下系统 -- 班级管理。

教务处系统怎么能没有班级呢，我们来考虑班级要如何设计。

### 表结构规划

- 每个班级每年的学生、老师等都不一样，所以班级这个表需要记录班级的年份，也就是 class_year，和它的年级等信息。

```sql
create table classes(
    class_id number(5),
    year number(4),
    grade number(2),
    class number(2),
    location varchar2(20),
    create_date date,
    delete_date date
);
comment on table classes is '班级表';
comment on column classes.class_id is '班级编号';
comment on column classes.year is '年份';
comment on column classes.grade is '年级';
comment on column classes.class is '班级';
comment on column classes.location is '班级地点';
comment on column classes.create_date is '生效时间';
comment on column classes.delete_date is '失效时间';
```

- 每个班级有班主任，授课老师，而且班主任也兼任一门课程。每个老师的授课在 teachers 中都有记录，所以我们只要记录班级对应的老师即可。

```sql
create table class_teachers(
    class_id number(5),
    job_id number(5),
    head_teacher number(1),
    create_date date,
    delete_date date
);
comment on table class_teachers is '老师表';
comment on column class_teachers.class_id is '班级编号';
comment on column class_teachers.job_id is '工号';
comment on column class_teachers.head_teacher is '1.是班主任，2.不是班主任';
comment on column class_teachers.create_date is '生效时间';
comment on column class_teachers.delete_date is '失效时间';
```

每个班级都有学生，学生可能担任一个职位，班长、团委等，但有的不担任。每个班级的职位都是固定的，我们建一个职位表，这样不用每次都录入职位的名称。

```sql
create table class_students(
    class_id number(5),
    student_id number(5),
    postion_id number(5),
    create_date date,
    delete_date date
);
comment on table class_students is '学生职位表';
comment on column class_students.class_id is '班级编号';
comment on column class_students.student_id is '学生编号';
comment on column class_students.postion_id is '职位编号';
comment on column class_students.create_date is '生效时间';
comment on column class_students.delete_date is '失效时间';

create table position(
    position_id number(5),
    name varchar2(100),
    create_date date,
    delete_date date
);
comment on table position is '职位';
comment on column position.position_id is '职位编码';
comment on column position.name is '职位名称';
comment on column position.create_date is '生效时间';
comment on column position.delete_date is '失效时间';
```

这些表的关系是：
{{< mermaid >}}
classDiagram
class classes{
+number(5) class_id
+number(4) year
+number(2) grade
+varchar2(20) location
+date create_date
+date delete_date
}
class class_students{
+number(5) class_id
+number(5) student_id
+number(5) postion_id
+date create_date
+date delete_date
}
class position{
+number(5) position_id
+varchar2(100) name
+date create_date
+date delete_date
}
class class_teachers{
+number(5) class_id
+number(5) job_id
+number(1) head_teacher
+date create_date
+date delete_date
}
class teachers{
+varchar2(18) ard_id
+varchar2(18) tudent_id
+varchar2(18) arent
+varchar2(11) arent_phone
+date create_date
+date delete_date
}
class courses{
+number(5) course_id
+varchar2(100) name
+date create_date
+date delete_date
}
classes --|> class_students
class_students --|> position
classes --|> class_teachers
adasad
class_teachers --|> teachers
teachers --|> courses

{{</ mermaid >}}

### 登记学生资料

这就是我们之前依据登记在 people 中，但还未登记为学生的人员资料。

```sql
SELECT * FROM people WHERE card_id LIKE '12345678901235%';
```

1. 登记为学生，插入到 students 表中

```sql
INSERT INTO students
SELECT card_id,
CASE
	WHEN ROWNUM <10 THEN '09000'||ROWNUM
	WHEN ROWNUM >=10 AND ROWNUM <100 THEN '0900'||ROWNUM
	WHEN ROWNUM >=100 THEN '090'||ROWNUM
END student_id,
people.name||'妈',NULL,SYSDATE,NULL
FROM people WHERE card_id LIKE '12345678901235%';
```

### 登记班级资料

资料较多，请查看附件<a href="../attach/ins-classess" target="_blank">insert classes</a>

如果操作没有问题，执行下面查询，你将看到每个班级的授课老师，和是否是班主任：

```sql
SELECT classes.class_id,
       classes.grade,
       classes.CLASS,
       people.NAME,
       courses.NAME,
       CASE head_teacher WHEN 1 THEN '班主任' ELSE '' END AS 职位
  FROM class_teachers, classes, teachers, people, courses
 WHERE class_teachers.class_id = classes.class_id
   AND teachers.job_id = class_teachers.job_id
   AND courses.course_id = teachers.course_id
   AND people.card_id = teachers.card_id
 ORDER BY class_id, grade, courses.NAME;

CLASS_ID GRADE CLASS NAME                                     NAME                                                                             职位
-------- ----- ----- ---------------------------------------- -------------------------------------------------------------------------------- ---------
      17     5     3 周才哲                                   科学5
      17     5     3 郑睿明                                   美术5
      17     5     3 赵英悟                                   英语5
      17     5     3 孙天纵                                   计算机基础5
      17     5     3 沈鸿雪                                   语文5                                                                            班主任
      17     5     3 魏宏硕                                   道德与法治5
      17     5     3 冯经业                                   音乐5
      18     6     3 陈冰烟                                   体育6
      18     6     3 陈咏志                                   数学6
      18     6     3 冯茂学                                   科学6
      18     6     3 魏美怡                                   美术6
      18     6     3 刘咏思                                   英语6
      18     6     3 蒋冰双                                   计算机基础6
      18     6     3 赵博容                                   语文6                                                                            班主任
      18     6     3 赵昊乾                                   道德与法治6
      18     6     3 周天巧                                   音乐6

```

### 练习

请查询以下信息，还没分配班级的老师的姓名、工号、薪水、和对应课程名称。

## 第四天 马上月考了

### 排位表

- 考试时间表

**exam_schedule**

| 字段       | 数据类型    | 说明         |
| :--------- | :---------- | :----------- |
| exam_name  | varchar(30) | 考试唯一编码 |
| exam_id    | number(5)   | 考试流水码   |
| grade      | number(5)   | 年级         |
| course_id  | number(5)   | 课程 ID      |
| start_time | date        | 开始时间     |
| end_time   | date        | 结束时间     |

{{< details title="提示" open=false >}}

```sql
create table exam_schedule(
    exam_name varchar(30),
    exam_id number(5),
    grade number(5),
    course_id number(5),
    start_time date,
    end_time date
);
comment on table exam_schedule is '考试时间表';
comment on column exam_schedule.exam_name is '考试唯一编码';
comment on column exam_schedule.exam_id is '考试流水码';
comment on column exam_schedule.grade is '年级';
comment on column exam_schedule.course_id is '课程 ID';
comment on column exam_schedule.start_time is '开始时间';
comment on column exam_schedule.end_time is '结束时间';
```

{{</ details >}}

- 位置表

**exam_locations**

| 字段        | 数据类型     | 说明         |
| :---------- | :----------- | :----------- |
| exam_name   | varchar(30)  | 考试唯一编码 |
| exam_id     | number(5)    | 考试流水码   |
| class_id    | number(5)    | 班级 id      |
| seat_number | number(5)    | 座位号       |
| score       | number(10,2) | 成绩         |

{{< details title="提示" open=false >}}
创建 exam_locations 表

```sql
create table exam_locations(
    exam_name   varchar(30),
    exam_id     number(5),
    class_id    number(5),
    seat_number number(5),
    score       number(10,2)
);
comment on table exam_locations is '考试位置表';
comment on column exam_locations.exam_name   is '考试唯一编码';
comment on column exam_locations.exam_id     is '考试流水码';
comment on column exam_locations.class_id    is '班级 id';
comment on column exam_locations.seat_number is '座位号';
comment on column exam_locations.score       is '成绩';
```
{{</ details >}}


### 导入数据

## 第五天 出成绩了

### 导入成绩

### 查看每一门课的第一名

### 查看每一班级第一名

### 按照平均分给班级排名

### 查看每个班级前 3 名

### 查任意一个学生的班级排名和年纪排名以及是否满足班级平均分和年纪平均分
