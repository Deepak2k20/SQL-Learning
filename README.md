# Learn-SQL

What is SQL?

SQL stands for Structured Query Language \
SQL lets you access and manipulate databases \
SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987

What can SQL Do?

SQL can execute queries against a database\
SQL can retrieve data from a database\
SQL can insert records in a database\
SQL can update records in a database\
SQL can delete records from a database\
SQL can create new databases\
SQL can create new tables in a database\
SQL can create stored procedures in a database\
SQL can create views in a database\
SQL can set permissions on tables, procedures, and views

Some of The Most Important SQL Commands:

SELECT - extracts data from a database\
UPDATE - updates data in a database\
DELETE - deletes data from a database\
INSERT INTO - inserts new data into a database\
CREATE DATABASE - creates a new database\
ALTER DATABASE - modifies a database\
CREATE TABLE - creates a new table\
ALTER TABLE - modifies a table\
DROP TABLE - deletes a table\
CREATE INDEX - creates an index (search key)\
DROP INDEX - deletes an index

I have taken a sample database table Customer whose fields are - CustomerName, ContactName, Address, City, PostalCode, Country. \
I have taken a sample database table Products which fields are - ProductID, ProductName, SupplierID, CategoryID, Unit, Price.\
I have taken a sample database table OrderDetails which fields are - OrderDetailID, OrderID, ProductID, Quantity \
I have taken a sample database table Orders which fields are - OrderID, CustomerID, EmployeeID, OrderDate, ShipperID.

SQL JOIN ?\
A JOIN clause is used to combine rows from two or more tables, based on a related column between them.

Let's look at a selection from the "Orders" table:

OrderID	CustomerID	OrderDate\
10308	2	1996-09-18\
10309	37	1996-09-19\
10310	77	1996-09-20\
Then, look at a selection from the "Customers" table:

CustomerID	CustomerName	ContactName	Country\
1	Alfreds Futterkiste	Maria Anders	Germany\
2	Ana Trujillo Emparedados y helados	Ana Trujillo	Mexico\
3	Antonio Moreno Taquería	Antonio Moreno	Mexico\
Notice that the "CustomerID" column in the "Orders" table refers to the "CustomerID" in the "Customers" table. The relationship between the two tables above is the "CustomerID" column.

Then, we can create the following SQL statement (that contains an INNER JOIN), that selects records that have matching values in both tables:


	

