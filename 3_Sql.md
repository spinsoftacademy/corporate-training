# SQL Training

## Session 1: Database
* Create/Drop Database
   * create database training_db;
   * drop database training_db;
* List all databases
   * show databases;
* Select Database
   * use training_db;   
* Create User
  * CREATE USER 'naresh'@'localhost' IDENTIFIED BY 'pass123';
* Grant Privileges
  * GRANT ALL ON naresh.* TO 'training_db'@'localhost';
   
 ## Session 2: CRUD Operations
 * Datatypes  - integer, varchar, date, timestamp
 * Create Table
     * create table users( id int, name varchar(100), email varchar(100), dob date , created_at timestamp );
 * Drop Table
     * drop table users;
 * Insert Records
 * Update Records
 * Delete Records
 * Select Records
 
 ## Session 3: Restricting Records
 * select * from users where email='nareshkumarh@live.com' and password='pass123';
 * select * from users where dob IS NULL;
 * select * from users where dob IS NOT NULL;
 * select * from employees where salary > 10000;
 * select * from employees where salary between 10000 and 20000;
 * select * from employees where city in ('CHENNAI','BANGALORE');
 * * select * from employees where city in ('CHENNAI','BANGALORE');
 
 ## Session 4: Sorting
 * select * from users order by name;
 * select * from users order by name ASC;
 * select * from users order by name DESC;
 * select * from users order by name,dob DESC;
 
 ## Session 5: Constraints
* Not Null
* Unique
* Primary Key
* Check 
* Foreign Key
* Example:
     * create table users ( id int primary key auto_increment, name varchar(100) not null, email varchar(100) , unique (email) );
 
 ## Session 6: Aggregate Functions
 * select count(*), min(salary), max(salary), avg(salary), sum(salary) from employees;
 * select department_name, count(*), min(salary), max(salary), avg(salary), sum(salary) from employees group by department_name;
 * select department_name, count(*), min(salary), max(salary), avg(salary), sum(salary) from employees group by department_name having count(*) > 5;
 
## Session 7: Joins

## Session 8: SubQueries
