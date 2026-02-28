# SQL Internship - Day 1

This repository contains my Day 1 SQL assignment given during internship.

## What I Did in Day 1
- Created a database and Employees table
- Inserted sample data
- Wrote 10 SELECT queries
- Used WHERE condition for filtering

## Table Structure

CREATE TABLE Employees (
    EmpID INT PRIMARY KEY,
    Name VARCHAR(50),
    Department VARCHAR(50),
    Salary INT,
    City VARCHAR(50)
);

## Queries Practiced (10)

-- 1. Show all employees

SELECT * FROM Employees;

-- 2. Show IT department employees

SELECT * FROM Employees
WHERE Department = 'IT';

-- 3. Employees with salary greater than 50000

SELECT * FROM Employees
WHERE Salary > 50000;

-- 4. Employees from Delhi

SELECT * FROM Employees
WHERE City = 'Delhi';

-- 5. Employees with salary less than 45000

SELECT * FROM Employees
WHERE Salary < 45000;

-- 6. HR department employees (Name and Salary)

SELECT Name, Salary FROM Employees
WHERE Department = 'HR';

-- 7. Employees from Noida

SELECT Name FROM Employees
WHERE City = 'Noida';

-- 8. Employee with salary equal to 60000

SELECT * FROM Employees
WHERE Salary = 60000;

-- 9. Show only Name and Department

SELECT Name, Department FROM Employees;

-- 10. Employee with EmpID = 3

SELECT * FROM Employees
WHERE EmpID = 3;

## Conclusion

I successfully created the table, inserted data and executed all 10 queries in my SQL tool.

— Harshit Gaur-
