# 🍕 Pizza Sales SQL Analysis Project Report

## 1. Introduction

### Project Background

Businesses rely heavily on data analytics to understand customer behavior, improve operational efficiency, and maximize revenue. This project focuses on analyzing pizza sales data using SQL to uncover valuable business insights regarding sales performance, product popularity, customer ordering behavior, and revenue generation.

### Project Objectives

- Analyze overall sales performance.
- Calculate total revenue generated.
- Identify top-selling pizza products.
- Understand customer ordering patterns.
- Discover peak business hours.
- Analyze category-wise performance.
- Measure revenue contribution by products.
- Generate actionable business recommendations.

### Technologies Used

- MySQL
- SQL
- Git & GitHub
- Excel / Power BI

---

## 2. Dataset Overview

The dataset consists of four relational tables:

### Orders
- order_id
- date
- time

### Order Details
- order_details_id
- order_id
- pizza_id
- quantity

### Pizzas
- pizza_id
- pizza_type_id
- size
- price

### Pizza Types
- pizza_type_id
- name
- category
- ingredients

---

## 3. Database Schema

Orders
│
├── Order Details
│
├── Pizzas
│
└── Pizza Types

---

## 4. Business Questions

### Basic Analysis

1. Retrieve the total number of orders placed.
2. Calculate total revenue generated.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types.

### Intermediate Analysis

6. Find total quantity sold by category.
7. Determine order distribution by hour.
8. Find category-wise distribution.
9. Calculate average pizzas ordered per day.
10. Identify top 3 pizzas by revenue.

### Advanced Analysis

11. Calculate revenue contribution percentage.
12. Analyze cumulative revenue over time.

---

## 5. SQL Solutions

### SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- INNER JOIN
- Aggregate Functions
- Subqueries
- Window Functions

---

## 6. Results

### Key Findings

- Calculated total orders and revenue.
- Identified highest-priced pizza.
- Determined most popular pizza size.
- Found top-selling pizza types.
- Analyzed peak order hours.
- Measured category performance.
- Identified highest revenue-generating pizzas.

---

## 7. Insights

### Customer Behavior

- Orders peak during lunch and dinner hours.
- Large pizzas are the most popular size.
- A small number of pizzas account for most sales.

### Revenue Insights

- Revenue is concentrated among top-performing pizzas.
- Certain categories consistently outperform others.

---

## 8. Recommendations

### 1. Promote Best-Selling Pizzas

Increase visibility of top-performing pizzas through promotions and featured menu placement.

### 2. Optimize Peak-Hour Operations

Schedule more staff during lunch and dinner rush periods.

### 3. Improve Low-Selling Products

Use discounts and combo offers to boost demand.

### 4. Expand High-Revenue Categories

Introduce additional pizzas within successful categories.

### 5. Build a Business Dashboard

Track KPIs such as:
- Revenue
- Orders
- Category Performance
- Hourly Trends

---

## Conclusion

This project demonstrates practical SQL skills through real-world business analysis. Using joins, aggregations, subqueries, and window functions, valuable insights were generated regarding customer behavior, product performance, and revenue trends.
