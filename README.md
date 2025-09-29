📚 Task 5 – SQL Joins (Inner, Left, Right, Full)
🎯 Objective

The objective of this task is to practice using SQL joins to combine data from multiple tables. After this task, you will be able to:

🔹 Retrieve data from multiple tables using INNER, LEFT, RIGHT, and FULL joins.

🔹 Understand cross join, natural join, and self-join.

🔹 Analyze relationships between tables.

🛠 Tools Used

DB Browser for SQLite

MySQL Workbench

##🧠 Key SQL Concepts

INNER JOIN
🔹 Returns only rows with matching values in both tables.

LEFT JOIN (LEFT OUTER JOIN)
🔹 Returns all rows from the left table, and matching rows from the right table; NULL if no match.

RIGHT JOIN (RIGHT OUTER JOIN)
🔹 Returns all rows from the right table, and matching rows from the left table; NULL if no match.

FULL OUTER JOIN
🔹 Returns all rows when there is a match in either the left or right table.

CROSS JOIN
🔹 Returns the Cartesian product of the tables (all possible combinations).

NATURAL JOIN
🔹 Automatically joins tables on columns with the same name.

SELF JOIN
🔹 A table joined to itself, useful for hierarchical or comparison queries.

##💡 Examples & Outputs

INNER JOIN: Lists only customers who have orders.

LEFT JOIN: Lists all customers, even if they have no orders.

RIGHT JOIN: Lists all orders, even if some customer info is missing.

FULL OUTER JOIN: Combines LEFT and RIGHT join results.

CROSS JOIN: Produces all possible pairs of customers and orders.

SELF JOIN: Finds pairs of customers in the same city.

##❓ Interview Q&A

Difference between INNER and LEFT JOIN?
🔹 INNER JOIN returns only matching rows; LEFT JOIN returns all left table rows even without a match.

What is a FULL OUTER JOIN?
🔹 Returns all rows from both tables; missing matches are NULL.

Can joins be nested?
🔹 Yes, you can join multiple tables in a single query.

How to join more than 2 tables?
🔹 By chaining multiple JOIN clauses.

What is a CROSS JOIN?
🔹 Produces all combinations of rows from both tables.

What is a NATURAL JOIN?
🔹 Automatically joins on columns with the same name.

Can you join tables without foreign key?
🔹 Yes, using columns with matching values.

What is a SELF JOIN?
🔹 Joining a table to itself to compare rows.

What causes Cartesian product?
🔹 CROSS JOIN or missing join conditions.

How to optimize joins?
🔹 Use indexes, minimize columns in SELECT, avoid unnecessary joins.
