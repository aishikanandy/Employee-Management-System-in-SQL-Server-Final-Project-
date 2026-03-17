## Employee Management System in SQL Server

## Objective:

- Create a database to manage employees and their departments.
  
- Implement tables, relationships, and various SQL operations like joins, views, functions, stored procedures, and security roles.

## Database Structure:

- Departments Table: To store department details (DepartmentID, DepartmentName).
  
- Employees Table: To store employee details (EmployeeID, FirstName, LastName, DepartmentID, Salary).
  
- Add constraints:
  
    - UseDepartmentID as a primary key in the Departments table.
      
    - UseEmployeeID as aprimary key in the Employees table.
      
    - Establish a foreign key relationship between Employees.DepartmentID and Departments.DepartmentID.

## Sample Queries:

- Use JOINS to retrieve employee names along with their department names.
  
- Use OFFSET FETCH for pagination.
  
- Create a view that displays high-salaried employees (salary > 5000).
  
- Create a user-defined function to calculate annual salary.
  
- Create a stored procedure to insert a new employee record.
  
- Work with server and database roles:
  
    - Create a database role and assign permissions to view data.
      
    - Assign a server role to manage database backup.
 
## Summary

- The project successfully demonstrated how to design a complete SQL Server system by creating databases, tables, relationships, constraints, views, functions, and stored procedures.

- It provided hands-on experience with essential SQL concepts such as joins, pagination, role management, and data manipulation.

- Overall, the project strengthened understanding of database design, security, and real-world SQL operations used in professional environments.

## Author

Aishika Nandy

