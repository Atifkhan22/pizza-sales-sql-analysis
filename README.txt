#  Pizza Sales Analysis using MySQL

##  Overview

This project analyzes a pizza restaurant sales dataset using MySQL. The goal is to answer real-world business questions by writing SQL queries ranging from basic aggregations to advanced analytical queries.

---

##  Dataset

The project uses four CSV files:

- `orders.csv`
- `order_details.csv`
- `pizzas.csv`
- `pizza_types.csv`

These files were imported into MySQL using the **Table Data Import Wizard**.

---

##  Database Schema

The database consists of four tables:

- **orders**
- **order_details**
- **pizzas**
- **pizza_types**

The database schema is available in:

```
schema.sql
```

---

##  Project Structure

```
SQL PROJECT/
│
├── pizza_sales/
│   ├── order_details.csv
│   ├── orders.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── queries/
│   ├── 01_basics.sql
│   ├── 02_intermediate.sql
│   └── 03_advanced.sql
│
├── schema.sql
└── README.md
```

---

##  SQL Concepts Used

- SELECT Statements
- Filtering
- Aggregate Functions
- GROUP BY
- ORDER BY
- INNER JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- Ranking Functions

---

##  Business Questions Solved

### Basic

- Retrieve the total number of orders placed.
- Calculate the total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Identify the most common pizza size ordered.
- List the top 5 most ordered pizza types.

### Intermediate

- Calculate the total quantity ordered for each pizza category.
- Determine the distribution of orders by hour.
- Analyze category-wise pizza distribution.
- Calculate the average number of pizzas ordered per day.
- Find the top 3 pizza types based on revenue.

### Advanced

- Calculate the percentage contribution of each pizza category to total revenue.
- Analyze cumulative revenue over time.
- Identify the top 3 pizza types by revenue within each category.

---

##  How to Run

1. Create a new database in MySQL.
2. Execute `schema.sql` to create the required tables.
3. Import the CSV files into their respective tables.
4. Run the SQL scripts inside the `queries` folder.

---

##  Tools Used

- MySQL 8.0
- MySQL Workbench
- Visual Studio Code
- Git & GitHub

---

## Skills Demonstrated

- SQL Query Writing
- Data Analysis
- Data Aggregation
- Relational Database Management
- Business Insight Generation
- Window Functions
- Query Optimization
- Data Modeling

---

## Author

**Atif Khan**

M.Sc. Bioinformatics | Aspiring Data Analyst
