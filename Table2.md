# inserting data
CREATE DATABASE cats;
USE cats;
CREATE TABLE cat( name VARCHAR(20),
                  age INT);
    DESC cat;
INSERT INTO cat(name,age)
VALUES ("charlie",10),
       ("sadie",3),
       ("lazy Bear",1);
  SELECT * FROM cat;
       
