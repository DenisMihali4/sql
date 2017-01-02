# sql
СОЗДАЕМ БАЗУ
create database student;
СОЗДАЕМ ТАБЛИЦУ

create table lecture(
 id int not null AUTO_INCREMENT primary key,
 title varchar(35),
 description varchar(35) NOT NULL,
 startime varchar(25) NOT NULL,
 ENDtime varchar(35),
 LectureROOM int not null);
 
 ДАНЫЕ В ТАБЛИЦУ 
 
 INSERT into student(title,description,startime,endtime,LectureROOM)
      VALUES("Introduction to Java",
      "Java basics",
      "22.12.2016-19:15",
      "22.12.2016-21:15",
      204);
