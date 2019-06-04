// create database
CREATE DATABASE home; 
// use database
use home;
//create table
CREATE TABLE people(
first_name VARCHAR(20),
last_name VARCHAR(30),
age INT);
// show the table
DESC people;
// insert 1st person
INSERT INTO people(first_name,last_name,age)
VALUES('tina','yadav',20);
// select 
SELECT * FROM people;
//insert 2nd person
INSERT INTO people(age,last_name,first_name)
VALUES(23,'kumari','soni');
//select
SELECT * FROM people;
// insert multiple person
INSERT INTO people( first_name,last_name,age)
VALUES('linda','belchar',43),
('philip','frond',32),
('calvin','fisco',30);
//select
SELECT * FROM people; 
