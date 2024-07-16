//mysql syntax is case insensitive
//mysql is a declarative programming language
//starting command in terminal
mysql -u root -p 
//followed by password

SHOW DATABASES;//to see all the available databases

->CREATE DATABASE database_name;//to create a new datatbase
ex. CREATE DATABASE filmsdatabase;

->DROP DATABASE database_name//to delete the entire database

->USE database_name;//use the particular database to perform quries and create tables in that database

->CREATE TABLE table_name( var1 datatype, var2 datatype);
ex. CREATE TABLE MOVIES( NAME varchar(50) , RATINGG Integer);

->desc table_name;// describes the table

->INSERT INTO table_name ( var1 , var2);
->INSERT INTO table_name (var1_name, var2_name) VALUES ( var1_value,var2_value); // used to order the insertion of values
ex.INSERT INTO movies (Rating , Name) VALUES (3 , "Thor dark world"), (5,"Iron Man"), (4,"Captain marvel");//syntax to insert multiple quries together

->SELECT * FROM table_name;//prints the table where * represents all
eg. SELECT Rating from movies;//prints only rating column

//conditioning in MYSQL
> WHERE CLAUSE

-> SELECT * FROM movies WHERE condition;
eg. SELECT * FROM movies WHERE rating > 5;// prints only columns having rating > 5
eg. SELECT * FROM movies WHERE rating > 5 AND/OR rating<3;//clubing multiple conditions
eg. SELECT * FROM movies WHERE name = "Iron man";
eg. DELETE FROM movies WHERE name = "Iron man';

->UPDATE movies Set Rating = 5 WHERE name='Infinity war'; //used for updating values




