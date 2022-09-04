# SQLPractice
## Day 1

```

create database university;
use university;
show tables;

create table students (id varchar(5), name varchar(20), dept_name varchar(20));

insert into students values('24746', 'Schrefl', 'History');
insert into students values('79352', 'Rumat', 'Finance');
insert into students values('79329', 'Velikovs'); #Fails
insert into students (id, name) values('79329', 'Velikovs');

drop table students;

create table students (id varchar(5) not null, name varchar(20) not null, dept_name varchar(20) not null);

select * from students;
select id, name, dept_name from students;
```