# SQL-Challenge
There were 6 total tables included in the CSV dataset that had to be imported in order for this challenge: 

titles
employees
departments
dept manager
department employees 
salaries


There are two "main" tables: departments and employees. The other tables relate to these two tables. Departments has the dept_no primary key while employees holds the emp_no primary key and the other four tables have at least one of those two fields as foreign keys.

Departments 1-to-many to dept_emp
Employees many-to-many to titles
Employees many-to-many to salaries 
Employees many-to-1 to dept_emp
Employees many-to-1 to dept_manager
