 # SqlRepo ASSIGNMENT

## Question 1 - Database Creation ##

- Creating a database with a name School using CREATE DATABASE School query. Then before using DROP statement we have to take Backup of School Database by right click on tools then bacKup by giving specific location where you want the backup to be stored.Next Restore the database from backup file in SQL Server.
- Writing SQL statement to create a simple table Locations including columns country_id, country_name and region_id.
- Writing a SQL statement to rename the table Locations to Locations_new.  
- Writing a SQL statement to add a column region_name to the table locations.  
- Writinga SQL statement to add a column ID as the first column of the table locations.  
- Writing a SQL statement to add a column state_province after region_id to the table locations.  

## Question 2 - Constraints ##

- Writing a SQL query to create the below table with (agent_name,agent_code,working_area).
- Writing a SQL query to create a table to achieve UNIQUE constraints for ord_num.
- Writing SQL query to check UNIQUE values on more columns.
- Writing a SQL check constraint for commission column.
- Adding check constraint using alter table statement
- Adding check constraints on multiple columns using AND,OR.

## Question 3 - Distinct where clause query ##

Creating a table named Salesman with following columns Salesman_id, Name, City, Commission.
Selecting Salesman_id column as primary key and using identity for auto increment.
Writing a query for displaying all the records from salesmantable.
Using distinct clause to get the distinct name of the city
Using <> for getting all the city names except paris.
using wheere,AND fgetting the for getting the city records with commission>0.14 and city is paris.
Using order by for getting the records of the commission in ascending order.

## Question 4 - Aggregate functions and Top clause ##

Restored the database from AdventureworksDW2019.
sorted the Lastname from the Dimcustomer table.
Using the TOP clause to get the top 20 products from dimproduct table.
using top and percent to get the 50 percentage of customers from DimCustomer table.
Using the max and min functions to get the maximum and minimum yearly income from the DimCustomer.

## Question 5 ##

- Write a SQL query to Select distinct records of EmailAddress where the EmailAddress having a letters combination "vi" from DimEmployee table 
- Write a SQL query to find english product name starts with 'b' and ends with 'e' in EnglishProductName column from DimProduct table 
- Write a SQL statement to selects all english product names have "r" in the second position from EnglishProductName column  in DimProduct Table 
- write a SQL statement selects to select FirstName, DepartmentName, Title as specific columns and show who are working as 'Accountant' and 'Chief Financial Officer' from Title colum from DimEmployee table 
- Write a SQL Aliase statement to show FirstName and LastName  as Employee Full Name using hot coding from DimEmployee Table 
- Write a SQL query to find minimum unit price from UnitPrice column in FactInternetSales table. 
- Write a SQL query to find total sales amount from SalesAmount column in FactInternetSales table. 
- Write a SQL query to find average tax amount from Taxamt column in FactInternetSales table.

## Question 6 - Union ##

-  dept. table with mentioned data and inserting values into it.
- Apply Join on Employee and Department tables using the common column DeptID.
- SQL query to display Dname, Avg. salary of Each dept. using Joins and Group by Clauses.
- Using AdventureWorksDW2019 database and Writing a SQL query to display FirstName and BirthDate and birthdate should be between 01-01-1985 to 01-12-1985 from DimCustomer and DimEmployee tables using Union and Union all functions.

 ## Question 7 ##
- Create Employee_details table and ProjectDetail table and inserting values in to it.
- Getting employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for those employee which have assigned project already.
- Getting employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for all employee even they have not assigned project.
- Get all project name even they have not matching any employeeid, in left table, order by firstname from "EmployeeDetail" and "ProjectDetail".
- Get complete record(employeename, project name) from both tables([EmployeeDetail], [ProjectDetail]), if no match found in any table then show NULL.
 
## Question 8 ##

- Write a query to get FirstName in upper case as "First Name".
- Write a query for combine FirstName and LastName and display it as "Name" 
(also include white space between first name & last name)
- Get all employee details from EmployeeDetail table whose "FirstName" contains 'k' 
- Get all employee details from EmployeeDetail table whose "FirstName" end with 'h' 
- Get all employee detail from EmployeeDetail table whose "FirstName" not start 
   with any single character between 'a-p'

- Get all employee detail from EmployeeDetail table whose "FirstName" start with 'A' 
and contain 5 letters.
- Get all unique "Department" from EmployeeDetail table.
- Get the highest "Salary"  & Lowest "Salary" from EmployeeDetail table.
- Get the first name, current date, joiningdate and diff between current date 
and joining date in months.
- Get all employee details from EmployeeDetail table whose joining year is 2013.
- Get all employee details from EmployeeDetail table whose joining month is Jan(1).
- Get all employee details from EmployeeDetail table whose joining date 
     between "2013-01-01" and "2013-12-01".
- Select all employee detail with First name "Vikas","Ashish", and "Nikhil".
- Display first name and Gender as M/F.(if male then M, if Female then F)
- Select first name from "EmployeeDetail" table prifixed with "Hello "
- Get employee details from "EmployeeDetail" table whose Salary less than 700000
- Get employee details from "EmployeeDetail" table whose Salary 
     between 500000 than 600000
- Select second highest salary from "EmployeeDetail" table.
