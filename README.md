# sql
СОЗДАЕМ БАЗУ
create database student;
СОЗДАЕМ ТАБЛИЦУ

create table lecture(
 id int not null AUTO_INCREMENT primary key,
 title varchar(35),
 description varchar(35) NOT NULL,
 startime DATATIME NOT NULL,
 endtime DATATIME not null,
 LectureROOM int not null);
 
 ДАНЫЕ В ТАБЛИЦУ 
 
 insert into lecture (title,description,startime,ENDtime,LectureROOM)
      VALUES('Introduction to Java',
      Java basics',
      '2016-12-22 19:15:00',
      '2016-12-22 21:15:00',
      204);


ДОМ ЗАДАНИЕ ( ОБРАЩЕНИЕ К ТАБЛИЦЕ С ЗАПРОСОМ ДАТЫ НАЧАЛА И ДАТЫ КОНЦА) 
SELECT startime,endtime from student; 
