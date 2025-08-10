
📄 Overview

This document contains a series of SQL queries and their corresponding results, along with database index information.
It serves as a reference for common SQL operations, including filtering, joins, aggregation, and optimization with indexes.

📂 Contents

Selecting Customers from the USA

Query: Retrieve customers from the USA ordered by last name.

Result set of matching customers.

INNER JOIN Example

Query: Join orders with customers to retrieve order details.

Displays customer name alongside order information.

Subquery: Customers Who Spent Above Average

Query: Uses a subquery to find customers whose total spending exceeds the average spending.

Result includes customer name and total spent.

Aggregate: Average Order Value by Country

Query: Calculates average order totals grouped by country.

Shows comparative spending patterns.

Querying a View

Query: Retrieves data from a pre-defined view (customer_order_summary) with filtering and sorting.

Shows high-value customers.

Database Index Information

Displays indexes for:

customers table

orders table

order_items table

Useful for performance tuning.

📌 Usage
This PDF can be used as:

A learning resource for understanding SQL operations.

A reference guide for building queries and optimizing performance.

A documentation artifact for database design and query structure.

🛠 Tools & Environment
Database: MySQL / MariaDB (syntax matches)

Interface: MySQL Workbench (based on screenshots)

Language: SQL

