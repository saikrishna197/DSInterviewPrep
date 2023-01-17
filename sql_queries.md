SQL (Structured Query Language) is a programming language used to manage and manipulate relational databases.

Here are some basic SQL commands and examples:

SELECT: used to query a database and retrieve specific data.
Example:
SELECT first_name, last_name, salary FROM employees;


INSERT: used to add new data to a table.
Example:
INSERT INTO employees (first_name, last_name, salary) VALUES ('John', 'Doe', 50000);

UPDATE: used to modify existing data in a table.
Example:
UPDATE employees SET salary = 55000 WHERE first_name = 'John' AND last_name = 'Doe';

DELETE: used to delete data from a table.
Example:
DELETE FROM employees WHERE first_name = 'John' AND last_name = 'Doe';

WHERE: used to filter the result set of a SELECT, UPDATE, or DELETE statement.
Example:
SELECT first_name, last_name, salary FROM employees WHERE salary > 50000;


SQL aggregate functions are used to perform a calculation on a set of values and return a single value. Some common aggregate functions include:

COUNT(): returns the number of rows in a table or the number of non-NULL values in a column.
Example:
SELECT COUNT(*) FROM employees; 


SUM(): returns the sum of all non-NULL values in a column.
Example:
SELECT SUM(salary) FROM employees;

AVG(): returns the average of all non-NULL values in a column.
Example:
SELECT AVG(salary) FROM employees;


MIN(): returns the minimum non-NULL value in a column.
Example:
SELECT MIN(salary) FROM employees;

MAX(): returns the maximum non-NULL value in a column.
Example:
SELECT MAX(salary) FROM employees;

GROUP BY: groups rows by one or more columns, and can be used in combination with aggregate functions to calculate values for each group.
Example:
SELECT department, COUNT(*) FROM employees GROUP BY department;

HAVING: used to filter groups of rows based on a aggregate function.
Example:
SELECT department, COUNT(*) FROM employees GROUP BY department HAVING COUNT(*) > 5;
It is important to note that aggregate functions only work on numerical columns and will not work on text columns.

