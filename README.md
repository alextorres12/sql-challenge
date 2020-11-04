# SQL Challenge
Northwestern University Data Science Boot Camp

[Homework 9](https://nu.bootcampcontent.com/NU-Coding-Bootcamp/nu-chi-data-pt-08-2020-u-c/tree/master/02-Homework/09-SQL/Instructions)

## Data Engineering & Modeling
In this project, I analyzed CSV files of employee data to develop a database structure and create a table schema to best contain the data in those CSVs. I used [Quick Database Diagrams](http://www.quickdatabasediagrams.com) to sketch an ERD, including table relationships, key definitions, and data types. 

![ERD](https://github.com/alextorres12/sql-challenge/blob/main/Images/ERD.png)

After sketching the ERD, I wrote schema.sql to produce the desired database structure. Then, I used the CSV import function of PostgreSQL to import the data into my database. 

## Data Analysis
For this part of the project, I wrote queries using joins, aggregates, group-by, and order-by to produce the following results:

- A list of employees' ID number, last name, first name, sex and salary. 
- A list of all employees hired in the year 1986.
- A list of the managers of each department with department number, department name, employee ID, last name, and first name.
- A list of all employees with department name.
- A list of all employees with the whose name starts with "Hercules B."
- A list of all employees in the Sales department.
- A list of all employees in the Sales and Development departments.
- A list of the most common last names among employees. 
