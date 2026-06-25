# Pizza Sales Analysis using MySQL

## Overview

This project analyzes a pizza restaurant sales dataset using MySQL. The objective is to answer real-world business questions through SQL queries ranging from basic data retrieval to advanced analytical queries.

---

## Dataset

The project uses the following CSV files:

- `orders.csv`
- `order_details.csv`
- `pizzas.csv`
- `pizza_types.csv`

These files were imported into MySQL using the Table Data Import Wizard.

---

## Database Schema

The database consists of four tables:

- `orders`
- `order_details`
- `pizzas`
- `pizza_types`

The table definitions are available in `schema.sql`.

---

## Project Structure

```text
pizza-sales-sql-analysis/
│
├── pizza_sales/
│   ├── orders.csv
│   ├── order_details.csv
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

## SQL Concepts Used

- SELECT Statements
- Filtering
- Aggregate Functions
- GROUP BY
- ORDER BY
- INNER JOIN
- Subqueries
- Window Functions
- Common Table Expressions (CTEs)
- Ranking Functions

---

## Business Questions Solved

### Basic

- Retrieve the total number of orders placed.
- Calculate the total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Identify the most common pizza size ordered.
- List the top five most ordered pizza types along with their quantities.

### Intermediate

- Calculate the total quantity of each pizza category ordered.
- Determine the distribution of orders by hour of the day.
- Analyze the category-wise distribution of pizzas.
- Calculate the average number of pizzas ordered per day.
- Determine the top three pizza types based on revenue.

### Advanced

- Calculate the percentage contribution of each pizza category to total revenue.
- Analyze cumulative revenue over time.
- Determine the top three pizza types by revenue within each pizza category.

---

## Tools Used

- MySQL 8.0
- MySQL Workbench
- Visual Studio Code
- Git
- GitHub

---

## Skills Demonstrated

- SQL Query Writing
- Data Analysis
- Data Aggregation
- Relational Database Design
- Data Modeling
- Business Insight Generation
- Window Functions
- Query Optimization

---

## How to Run

1. Create a MySQL database.
2. Execute `schema.sql` to create the required tables.
3. Import the CSV files into their respective tables.
4. Run the SQL scripts inside the `queries` folder.

---

## Author

**Atif Khan**

M.Sc. Bioinformatics  
Aspiring Data Analyst