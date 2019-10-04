1.Install Mysql

2.Write query :-


show databases;

create database telusko;

use telusko;
create table student(name varchar(20), college varchar(20));

insert into student values ('navin','vsit'), ('Priya','bvit');
select * from student;