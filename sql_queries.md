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


