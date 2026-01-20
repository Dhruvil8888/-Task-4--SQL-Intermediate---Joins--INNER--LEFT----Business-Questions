🔗 Task 4: SQL Intermediate – JOINs (INNER, LEFT) & Business Questions
📌 Project Overview

This task focuses on using SQL JOIN operations to combine multiple relational tables and answer real-world business questions.
The objective is to understand how customer, order, product, and category data are linked and how businesses analyze performance using JOIN-based queries.

📂 Dataset

One of the following relational datasets was used:

Chinook Database (recommended for SQL learning)

Northwind Dataset

E-commerce Dataset (Customers, Orders, Products, Categories)

Each dataset follows a relational structure with primary keys and foreign keys.

🛠 Tools Used

Primary: MySQL / PostgreSQL

Alternative: SQLite + DB Browser

GUI Tools: MySQL Workbench, pgAdmin, DBeaver

📁 Project Files
File Name	Description
joins_queries.sql	SQL file containing all JOIN queries with comments
joined_output.csv	Exported output from joined SQL queries
insights.txt	Text file with 3 summarized business insights
README.md	Project documentation
🔧 SQL Concepts Covered

INNER JOIN

LEFT JOIN

Multi-table JOINs

Table aliases (c, o, p, cat)

Aggregations on joined data

Business-driven SQL queries

🧩 Tasks Performed

Loaded multiple tables and verified primary–foreign key relationships.

Used INNER JOIN to combine orders with customer details.

Used LEFT JOIN to identify customers who never placed orders.

Joined orders and products to calculate total revenue per product.

Joined products and categories to analyze category-wise revenue.

Applied WHERE conditions for region-wise and date-wise analysis.

Used aliases to improve query readability and professionalism.

Exported joined query results to CSV format.

Stored all final queries in a reusable .sql file with comments.

📈 Business Insights (Summary)

A small number of top products contribute a large share of total revenue.

Some customers have never placed any orders, indicating re-engagement opportunities.

Certain product categories consistently outperform others in revenue contribution.
