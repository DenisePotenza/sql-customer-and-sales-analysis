# SQL Customer and Sales Analysis

## Project overview

This project analyzes sales performance and customer purchasing behavior using PostgreSQL.

The analysis focuses on two business questions:

1. Which days of the week generate the highest average sales in physical stores?
2. Who are the most loyal active customers, and which product category is most relevant to each customer?

## Business questions

### Physical store sales

- How much is sold on each day of the week?
- What is the average daily sales value?
- Which weekdays have the highest and lowest average sales?
- How many days had no sales during the analyzed period?

### Customer analysis

- Which active customers have the highest total revenue?
- How frequently do they purchase?
- What is their average order value?
- How diverse is their purchasing behavior?
- Which category is most frequently purchased by each loyal customer?

## SQL techniques demonstrated

- INNER JOIN and LEFT JOIN
- Common Table Expressions (CTEs)
- Temporary tables
- Aggregations with SUM, COUNT, AVG, MIN, and MAX
- CASE expressions
- COALESCE
- Date manipulation
- generate_series
- Window functions with ROW_NUMBER
- Business-oriented filtering and ranking

## Database

PostgreSQL

## Project structure

- `01_physical_store_sales_by_weekday.sql`: generates a complete calendar and analyzes physical-store sales by weekday.
- `02_loyal_customer_analysis.sql`: calculates customer metrics and identifies the predominant category for loyal customers.

## Main insights

The queries were designed to support decisions related to sales planning, customer segmentation, and retention opportunities.
