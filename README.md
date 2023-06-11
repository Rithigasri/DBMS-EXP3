# EXPERIMENT 03: SQL QUERY TO SHOW THE TOP N RECORDS OF THE TABLE USING LIMIT METHOD
## AIM:
To create an SQL query to show the top n records of the table using Limit method.

## ALGORITHM:
1. Create an SQL table employees with 5 rows and 4 columns
2. Insert sample data into the "employees" table
3. Retrieve and display the employee details
4. Add the LIMIT keyword followed by a number to the SELECT query. In this case, we limit the result to 3 rows
5. Execute the SQL program
6. View the output
## PROGRAM:
```
-- Create the employee table
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    department VARCHAR(50),
    salary DECIMAL(10, 2)
);

-- Insert sample data into the employee table
INSERT INTO employees (id, name, department, salary)
VALUES (1, 'John Doe', 'Sales', 5000),
       (2, 'Jane Smith', 'Marketing', 6000),
       (3, 'David Johnson', 'IT', 7000),
       (4, 'Emily Brown', 'Finance', 5500),
       (5, 'Michael Davis', 'HR', 4500);

-- Retrieve and display the employee details
SELECT * FROM employees
LIMIT 3;
```
## OUTPUT:
![image](https://github.com/Rithigasri/DBMS-EXP3/assets/93427256/1a9ecf05-8fde-47ad-9b57-8a91dd43510b)

## RESULT:
Thus,a SQL query is created to show the top n records of an table using Limit method.
