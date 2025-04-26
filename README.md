# SQL-Course

## 01-Feb
1.What is SQL or Why SQL ? <br>
2. What is different between Entity or attribute or tuples of records ? <br>
3. What is Database Schemas ?  <br>
4. What is Server or Database ? <br> 

## 02-Feb 

1. What is a primary key, and why is it important?
2. What is the difference between a primary key and a foreign key?
3. Explain the difference between DELETE, TRUNCATE, and DROP.
4. What are SQL constraints? Provide examples (e.g., NOT NULL, UNIQUE, CHECK).
5. suppose Amazon has stored much information about customers, products, orders, categories or more in the database tables. Customers want to change their information, which Sql commands should you use to solve this problem?
6. I have users or posts tables and I want a relationship between both tables and get information, so what is your approach, and how do you solve this problem ?

## 06-Feb
1. Write a sql query delete employees and posts tables from database.
2. what is the use case of ALTER TABLE and DROP TABLE?
3. write a sql query for DROP and TRUNCATE TABLE?
4. Let's suppose I have customers tables with customer_id, customer_name , salary, address, email, and phone and our clients need to change the customer_name columns what is your approach for solved these problems ?
5. Why we use  IF EXISTS or IF NOT EXISTS in SQL queries?
6. How do understand ADD and MODIFY Commands in Mysql?

## 07-Feb 
1. How to Create a Database abc if this database have already exists ?
2. Write a command to display all database name ?
3. Created Students table with id,s_name, age, email, phone and address attributes makes sure id is primary key and any columns have never store null values?
4. What is output of the code ( select * from students )
5. Explane this SQL query ( Truncate table ABC; )
6. What is the advantages or disadvantages of using drop commands ?
   
## 09-Feb
Mentions in your sql-day5 file at line numbers 48

## 13-Feb
1. What is Char or Varchar ?
2. What kind of data types should be defined for sotre name, email or phone number ?
3. How to store multiple records at a time ?
4. Write an SQL query for the created new column with datatypes varchar(30) and then changed this column into another names?
5. what do you understand about this query ( alter table employees to emp; )
6. what is output of this Sql query ( ADD COLUMN city VARCHAR(50) CHECK (city IN ('delhi', 'm')); )

## 22-Feb 
1. Write a SQL query to insert a new record into the "employees" table.
2. Write a SQL query to update the "quantity" column of the "products" table to 10 where the "product_id" is 5.
3. Write a SQL query to delete all records from the "orders" table where the "status" is 'cancelled'.
4. Write a SQL query to retrieve the names of all customers from the "customers" table in alphabetical order.
5. https://www.sqlzoo.net/wiki/SQL_Tutorial ( More practice ) 
6. https://www.w3schools.com/mySQl/mysql_create_db.asp ( DDL practice ) 

## 27-Feb 
1. null vs 'null'

## 28-Feb 
1. Write a SQL query to update the "price" column of the "course" table to 299 where the "course_id" is 5.
2. Write a SQL query to delete all records from the "orders" table where the "status" is 'cancelled'.
3. What is Filtering and Sorting?
4. Write a SQL query to retrieve all the columns from the "products" table where the "category" is 'Electronics' and the "price" is less than 1000.
5. Write a SQL query to retrieve the names of all customers from the "customers" table in alphabetical order.
6. Write a SQL query to retrieve the total number of course from the "course" table.
8. Write a SQL query to delete all records from the "customers" table where the "last_login_date" is older than 1 year. ( Optional ) 
9. Write a SQL query to insert new records into the "employees" table, selecting data from the "temp_employees" table.
10. Write a SQL query to update the "discount" column of the "orders" table by increasing it by 5% for all orders placed before a specific date.
11. What is different between Temporay table and View table ?

## 02-Mar
1. Let's suppose we have table structure like ,
   CREATE TABLE Persons (
    ID int NOT NULL,
    LastName varchar(255) NOT NULL,
    FirstName varchar(255) NOT NULL,
    Age int
);
  What is query for define the size of the dataset so what is your approach ?
## 16-Mar
1. https://leetcode.com/problems/recyclable-and-low-fat-products/?envType=study-plan-v2&envId=top-sql-50
2. https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true
3. https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true
4. https://www.hackerrank.com/challenges/weather-observation-station-1/problem?isFullScreen=true
5. https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true
6. https://leetcode.com/problems/big-countries/?envType=study-plan-v2&envId=top-sql-50

## 23-Mar 
1. What is the meaning of LIKE ‘%0%0%’ in SQL?
2. What do you mean by Data Sharing in DBMS?
Options: Pick one correct answer from below
a) Same data visible to everyone
b) Different data for everyone
c) Multiple versions of data
d) Anyone can access data
Solution description:- 
The act of sharing the same data resource with multiple applications or users is known as data sharing. In the case of DBMS when the same information is visible to everyone , it is called data sharing.

## 27-Mar
1. https://leetcode.com/problems/find-customer-referee/?envType=study-plan-v2&envId=top-sql-50
2. https://leetcode.com/problems/article-views-i/?envType=study-plan-v2&envId=top-sql-50
3. https://leetcode.com/problems/invalid-tweets/?envType=study-plan-v2&envId=top-sql-50
4. https://leetcode.com/problems/patients-with-a-condition/?envType=study-plan-v2&envId=top-sql-50
5. Which clause use for filter the records?
6. How can you remove or handle duplicated records from database tables?

## 26-April 
1. -- Retrieve each Product with the total,Maximum and average quantity of their sales.
2. -- Retrieve Product along with the total and average quantity of their purchases.
3. -- Retrieve product with an average sales quantity  whose sum is less than 2.


