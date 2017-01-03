# sql
СОЗДАЕМ БАЗУ
create database student;
СОЗДАЕМ ТАБЛИЦУ

create table lecture_1(
 id int not null AUTO_INCREMENT primary key,
 title varchar(35),
 description varchar(35) NOT NULL,
 startime DATETIME,
 endtime DATETIME,
 lectureROOM int not null );
 
 ДАНЫЕ В ТАБЛИЦУ 
 
insert into lecture_1(title,description,startime,endtime,lectureROOM)
VALUES('Introduction to Java','Java basics','2016.12.22 19:15:00','2016.12.22 21:15:00','204');


ДОМ ЗАДАНИЕ ( ОБРАЩЕНИЕ К ТАБЛИЦЕ С ЗАПРОСОМ ДАТЫ НАЧАЛА И ДАТЫ КОНЦА) 
SELECT startime,endtime from lecture_1; 
