---
title: "登记班级资料"
weight: 20
tags: ["SQL"]
categories: ["SQL"]
# bookComments: false
# bookSearchExclude: false
---


# 登记班级资料


## 登记classes基础资料

```sql
insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (1, 2010, 1, 1, '1栋1楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (2, 2010, 2, 1, '1栋2楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (3, 2010, 3, 1, '1栋3楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (4, 2010, 4, 1, '1栋4楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (5, 2010, 5, 1, '1栋5楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (6, 2010, 6, 1, '1栋6楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (7, 2010, 1, 2, '1栋7楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (8, 2010, 2, 2, '1栋8楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (9, 2010, 3, 2, '1栋9楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (10, 2010, 4, 2, '1栋10楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (11, 2010, 5, 2, '1栋11楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (12, 2010, 6, 2, '1栋12楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (13, 2010, 1, 3, '1栋13楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (14, 2010, 2, 3, '1栋14楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (15, 2010, 3, 3, '1栋15楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (16, 2010, 4, 3, '1栋16楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (17, 2010, 5, 3, '1栋17楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into classes (CLASS_ID, YEAR, GRADE, CLASS, LOCATION, CREATE_DATE, DELETE_DATE)
values (18, 2010, 6, 3, '1栋18楼', to_date('04-08-2023', 'dd-mm-yyyy'), null);

```


## 登记class_student资料

```sql
INSERT INTO class_students
SELECT  FLOOR(ROWNUM/45)+1 class_id,student_id,NULL,SYSDATE,NULL FROM students
```

## 登记职位表

```sql
insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (1, '班长', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (2, '副班长', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (3, '学习委员', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (4, '团委书记', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (5, '体育委员', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (6, '语文课代表', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (7, '数学课代表', to_date('04-08-2023', 'dd-mm-yyyy'), null);

insert into position (POSITION_ID, NAME, CREATE_DATE, DELETE_DATE)
values (8, '英语课代表', to_date('04-08-2023', 'dd-mm-yyyy'), null);
```

## 学生设置职位

```sql
UPDATE class_students SET postion_id = 1 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 2 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 3 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 4 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 5 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 6 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 7 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);

UPDATE class_students SET postion_id = 8 WHERE (class_id, student_id) IN
(SELECT class_id, MIN(student_id) student_id FROM class_students WHERE postion_id IS NULL GROUP BY class_id);
```

## 班级老师设置

```sql
INSERT INTO class_teachers
SELECT class_id, job_id, NULL, SYSDATE, NULL
  FROM classes,
       (SELECT NAME, MIN(job_id) job_id
          FROM courses, teachers
         WHERE teachers.course_id = courses.course_id
           AND job_id NOT IN (SELECT job_id FROM class_teachers)
         GROUP BY NAME) teacher
 WHERE NAME LIKE '%' || grade
   AND CLASS = 1;

INSERT INTO class_teachers
SELECT class_id, job_id, NULL, SYSDATE, NULL
  FROM classes,
       (SELECT NAME, MIN(job_id) job_id
          FROM courses, teachers
         WHERE teachers.course_id = courses.course_id
           AND job_id NOT IN (SELECT job_id FROM class_teachers)
         GROUP BY NAME) teacher
 WHERE NAME LIKE '%' || grade
   AND CLASS = 2;

INSERT INTO class_teachers
SELECT class_id, job_id, NULL, SYSDATE, NULL
  FROM classes,
       (SELECT NAME, MIN(job_id) job_id
          FROM courses, teachers
         WHERE teachers.course_id = courses.course_id
           AND job_id NOT IN (SELECT job_id FROM class_teachers)
         GROUP BY NAME) teacher
 WHERE NAME LIKE '%' || grade
   AND CLASS = 3;
```

## 班主任设置

```sql
UPDATE class_teachers SET head_teacher = 1
WHERE (class_id,job_id) IN
(SELECT class_id,MIN(job_id) job_id FROM class_teachers 
GROUP BY class_id);

UPDATE class_teachers SET head_teacher = 2
WHERE head_teacher IS NULL;
```