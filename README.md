# SQL Practice - Employees Database

## Project Overview

This project contains SQL practice queries using an Employees table. It is designed for beginners to learn and practice fundamental SQL concepts such as:

- SELECT
- WHERE
- GROUP BY
- HAVING
- TOP / LIMIT
- DISTINCT
- Comparison Operators
- Logical Operators
- IN & NOT IN
- BETWEEN
- LIKE Operator

The project includes the SQL script to create the table, insert sample data, and execute various SQL queries.

---

## Database Schema

Table Name: Employees

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| emp_id | INT | Employee ID |
| emp_name | VARCHAR(50) | Employee Name |
| department | VARCHAR(50) | Department Name |
| salary | INT | Employee Salary |
| city | VARCHAR(50) | Employee City |
| experience | INT | Years of Experience |

---

## Sample Data

The table contains 15 employee records from different departments such as:

- IT
- HR
- Finance
- Sales

Employees belong to different cities including:

- Hyderabad
- Bangalore
- Chennai
- Mumbai
- Pune

---

## SQL Topics Covered

### SELECT

- Display all records
- Display selected columns
- Filter department-wise information

### WHERE

- Salary conditions
- Department conditions
- City conditions
- Experience conditions

### GROUP BY

- Total salary department-wise
- Average salary
- Maximum salary
- Minimum experience
- Employee count

### HAVING

- Filter grouped results
- Average salary conditions
- Employee count conditions
- Total salary conditions

### TOP (SQL Server)

- Highest paid employees
- Most experienced employees
- Top Finance salaries
- Highest salary employee

Note: If you are using MySQL, replace TOP with LIMIT.

### DISTINCT

- Unique departments
- Unique cities
- Unique salaries
- Unique department-city combinations
- Unique experience values

### Comparison Operators

- Greater Than (>)
- Less Than (<)
- Greater Than or Equal To (>=)
- Less Than or Equal To (<=)
- Not Equal To (<>)

### Logical Operators

- AND
- OR
- NOT

### IN and NOT IN

- Filter multiple values
- Exclude multiple values

### BETWEEN

- Salary range
- Experience range
- Employee ID range

### LIKE Operator

- Starts with
- Ends with
- Contains
- Pattern matching

---

## How to Run

1. Open your SQL editor (SQL Server Management Studio, Azure Data Studio, MySQL Workbench, or any SQL editor).
2. Create a new database.
3. Execute the CREATE TABLE statement.
4. Execute the INSERT INTO statements.
5. Run the SQL queries one by one.

---

## Supported Databases

- Microsoft SQL Server
- MySQL (Use LIMIT instead of TOP)
- PostgreSQL (Use LIMIT)
- SQLite (Use LIMIT)
- Oracle SQL (Use FETCH FIRST n ROWS ONLY)

---

## Learning Outcomes

After completing this project, you will be able to:

- Write basic SQL queries
- Filter records using conditions
- Perform aggregation using GROUP BY
- Filter grouped data using HAVING
- Retrieve unique records
- Use comparison and logical operators
- Work with IN, BETWEEN, and LIKE operators
- Sort and retrieve top records

---

## Project Structure

```text
SQL-Practice/
│
├── README.md
├── create_table.sql
├── insert_data.sql
└── sql_practice_queries.sql
```

---

## Future Enhancements

- ORDER BY queries
- Aggregate Functions
- CASE statements
- JOINs
- Subqueries
- Views
- Stored Procedures
- Window Functions
- Indexes
- Constraints
- Transactions

---

## Author

Created as a beginner-friendly SQL practice project for learning and improving SQL querying skills.

---

If you found this project useful, consider giving it a star.
