# Restaurant Order & Revenue Analysis | SQL | Client: Local Melbourne restaurant in Lygon street


This project uses SQL to analyse restaurant menu and order data. It explores menu pricing, customer order behaviour, item popularity and high-value orders to support data-informed restaurant decisions.

## Business Questions

* What does the menu portfolio look like by category and price?
* Which categories have the most dishes and the highest average prices?
* What was the period of order activity?
* How many orders and items were processed?
* Which orders contained the largest number of items?
* Which menu items and categories were purchased most and least often?
* Which orders generated the highest spend, and what did customers purchase in those orders?

## Dataset

The analysis uses two relational tables:

| Table           | Description                                             |
| --------------- | ------------------------------------------------------- |
| `menu_items`    | Menu item ID, item name, category and price             |
| `order_details` | Order ID, order date, order details ID and menu item ID |

## Analysis Objectives

### 1. Menu Portfolio and Pricing Analysis

This section explores the structure of the menu by:

* Counting available menu items
* Reviewing the lowest- and highest-priced items
* Investigating Italian menu items and their price range
* Comparing the number of dishes across categories
* Calculating average price by category

### 2. Order Activity Analysis

This section examines transaction activity by:

* Identifying the date range of available orders
* Counting distinct orders and total items ordered
* Identifying orders with the highest number of items
* Counting orders containing more than 12 items

### 3. Revenue and High-Value Order Analysis

This section joins order and menu data to:

* Identify the most- and least-ordered menu items
* Analyse category-level purchasing patterns
* Calculate total spend by order
* Identify the top five highest-spend orders
* Review the category mix within high-value orders

## SQL Skills Demonstrated

* `SELECT`, `WHERE` and `ORDER BY`
* Aggregations: `COUNT()` and `AVG()`
* `GROUP BY` and `HAVING`
* `LEFT JOIN`
* Subqueries
* `LIMIT`
* Translating business questions into SQL analysis

## Repository Structure

```text
Objective01- MA_Res_Project.sql    # Menu portfolio and pricing analysis
Objective02_order_analyse.txt      # Order activity analysis
Objective03_revenue_analysis.txt   # Revenue and high-value order analysis
TotalProjectObjectives.md          # Project overview
```

## Timeline of the project

Ava Saeedi
[LinkedIn](https://www.linkedin.com/in/avasaeedi)
