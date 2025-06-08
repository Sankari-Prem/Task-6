# Task-6
This repository contains SQL practice queries performed on a fictional parks_and_recreation employee database. The database consists of two main tables:

employee_demographics

employee_salary

The queries cover a wide range of SQL concepts, from filtering and sorting to subqueries, common table expressions (CTEs), and window functions.

SQL 2.sql
This file contains basic to intermediate SQL queries using:

WHERE clause for filtering (e.g., based on name, salary, occupation, birth date).

Logical operators: AND, OR, NOT.

Pattern matching with LIKE.

Aggregation using GROUP BY and functions like AVG(), MAX(), MIN(), COUNT().

Sorting with ORDER BY.

Result limiting using LIMIT and offset-style pagination.

HAVING clause for post-aggregation filtering.

Objective:
To explore filtering, grouping, and sorting data in various ways, particularly focusing on employee names, age, gender, and salary.

SQL 8.sql
This file demonstrates the use of:

Subqueries for deriving aggregate values.

Window Functions including:

AVG() OVER(PARTITION BY ...)

SUM() OVER(...)

ROW_NUMBER(), RANK(), and DENSE_RANK()

Objective:
To analyze salary trends and rank employees by salary within gender groups using advanced SQL techniques.

SQL 9.sql
This file includes multiple Common Table Expressions (CTEs):

CTEs for breaking down complex queries into reusable blocks.

Joining CTEs for multi-step analysis, such as filtering high-earning employees born after a certain date.

Objective:
To simplify complex joins and aggregations using CTEs and demonstrate how to nest or chain them for richer insights.
