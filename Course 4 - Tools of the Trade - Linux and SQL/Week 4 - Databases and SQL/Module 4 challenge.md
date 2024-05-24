### Question 1
### How can SQL help a security analyst querying a table related to login attempts?

* [x] The analyst can efficiently find the login data they need.
* SQL will automatically distribute a report on suspicious login attempts.
* The analyst will get a live update on new login attempts.
* SQL will change authentication permissions to prevent unauthorized logins.

### Question 2
### What is a primary key?

* The first column in every table
* The first row in every table
* A column that contains null values
* [x] A column where every row has a unique entry

### Question 3
### Which of these SQL statements queries the `log_in_attempts` table? Select all that apply.

* [x] `SELECT * FROM log_in_attempts;`
* [x] `SELECT event_id, username FROM log_in_attempts WHERE event_id < 150;`
* `SELECT log_in_attempts FROM *;`
* `SELECT log_in_attempts FROM event_id;`

### Question 4
### Both an `employees` table and a `machines` table contain an `employee_id` column, and you want to return only the records that share a value in this column. Which keyword should be part of your query?

* `FULL OUTER JOIN`
* `WHERE`
* `BETWEEN`
* [x] `INNER JOIN`

### Question 5
### What does `WHERE department = 'Sales'` indicate in the following SQL query?

```sql
SELECT *

FROM employees

WHERE department = 'Sales';
```

* To only return the department column
* [x] To only return rows that match the filter
* To change all the values in the department column to 'Sales'
* To highlight the department column in the results

### Question 6
#### Which query returns all records that contain the character 'z' from the `name` column in the `employees` table?

* `SELECT name FROM employees WHERE name LIKE ‘%z’;`
* `SELECT name FROM employees WHERE name LIKE ‘z’;`
* [x] `SELECT name FROM employees WHERE name LIKE ‘%z%’;`
* `SELECT name FROM employees WHERE name = ‘z%’;`

### Question 7
#### You need to perform a SQL join. You want to return all the columns with records matching on the `device_id` column between the `employees` and `machines` tables. You also want to return all records from the `employees` table. Which of the following queries would you use?

* `SELECT * FROM employees RIGHT JOIN machines ON employees.device_id = machines.device_id;`
* `SELECT * FROM employees INNER JOIN machines ON employees.device_id = machines.device_id;`
* [x] `SELECT * FROM employees LEFT JOIN machines ON employees.device_id = machines.device_id;`
* `SELECT * FROM employees FULL OUTER JOIN machines ON employees.device_id = machines.device_id`

### Question 8
### You are working with the Chinook database. You want to return the company and country columns from the customers table. Replace --??? with the missing information to complete the query. (If you want to undo your changes to the query, you can click the Reset button.)

```sql
SELECT company, country
FROM customers;
```
### In what country is JetBrains s.r.o. located?

* [x] Czech Republic
* Germany
* United States
* Brazil

### Question 9
### You are working with the Chinook database and want to filter on the `hiredate` column to find all employees hired on or after '2003-10-17' (October 17, 2003). Replace --??? with the missing information to complete the query. (If you want to undo your changes to the query, you can click the Reset button.)
```sql
SELECT firstname,lastname,hiredate
FROM employees
WHERE hiredate >= '2003-10-17';
```
### How many employees were hired on or after October 17, 2003?

* 1
* 2
* 3
* [x] 4

### Question 10
### You are working with the Chinook database and are responsible for filtering for the customers that live in the city of 'Mountain View' and work for the company of 'Google Inc.' Replace --??? with the missing information to complete the query. (If you want to undo your changes to the query, you can click the Reset button.)

```sql
SELECT firstname, lastname, city, company
FROM customers
WHERE city = 'Mountain View' AND company = 'Google Inc.';
```

### How many customers live in Mountain View and work for Google Inc.?

* 3
* [x] 1
* 4
* 2