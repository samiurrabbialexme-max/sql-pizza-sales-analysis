# 🍕 Pizza Sales Analytics Project

![SQL](https://img.shields.io/badge/SQL-MySQL-blue)
![Python](https://img.shields.io/badge/Python-Data_Analysis-green)
![Analytics](https://img.shields.io/badge/Project-Business_Analytics-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project analyzes pizza sales data using **SQL**, **Python**, and **Data Visualization** techniques to uncover business insights related to customer behavior, product performance, sales trends, and revenue generation.

The goal is to transform raw transactional data into actionable business intelligence through structured querying, exploratory data analysis (EDA), and visualization.

---

## 🎯 Objectives

* Analyze overall sales performance.
* Calculate total revenue generated.
* Identify top-selling pizza products.
* Understand customer ordering behavior.
* Discover peak business hours.
* Analyze category and size preferences.
* Measure revenue contribution by products.
* Create visual reports and dashboards.

---

## 🛠️ Tech Stack

| Technology       | Purpose              |
| ---------------- | -------------------- |
| MySQL            | Database & Querying  |
| SQL              | Data Analysis        |
| Python           | Data Processing      |
| Pandas           | Data Manipulation    |
| Matplotlib       | Data Visualization   |
| Git & GitHub     | Version Control      |
| Jupyter Notebook | Exploratory Analysis |

---

## 📂 Dataset Structure

The dataset contains four relational tables:

### Orders

Stores order-level information.

| Column   |
| -------- |
| order_id |
| date     |
| time     |

### Order Details

Stores transaction details.

| Column           |
| ---------------- |
| order_details_id |
| order_id         |
| pizza_id         |
| quantity         |

### Pizzas

Stores pizza pricing and size information.

| Column        |
| ------------- |
| pizza_id      |
| pizza_type_id |
| size          |
| price         |

### Pizza Types

Stores pizza metadata.

| Column        |
| ------------- |
| pizza_type_id |
| name          |
| category      |
| ingredients   |

---

## 🗄️ Database Schema

```text
Orders
│
├── Order Details
│
├── Pizzas
│
└── Pizza Types
```

---

## 🔍 Business Questions

### Basic Analysis

* Total number of orders placed
* Total revenue generated
* Highest-priced pizza
* Most common pizza size ordered
* Top 5 most ordered pizza types

### Intermediate Analysis

* Quantity sold by category
* Orders distribution by hour
* Category-wise sales analysis
* Average pizzas ordered per day
* Top 3 pizzas by revenue

### Advanced Analysis

* Revenue contribution by pizza type
* Cumulative revenue analysis

---

## 📊 Python Analytics & Visualizations

The project extends beyond SQL analysis by performing Exploratory Data Analysis (EDA) using Python.

### Revenue Analysis

* Revenue by Category
* Revenue Trend Over Time
* Monthly Revenue Analysis

### Product Analysis

* Top 10 Revenue Generating Pizzas
* Top 10 Most Ordered Pizzas
* Category Performance

### Customer Behavior Analysis

* Orders by Hour
* Orders by Day of Week
* Weekend vs Weekday Analysis

### Product Preference Analysis

* Pizza Size Distribution
* Revenue Contribution Analysis
* Pareto (80/20) Analysis

---

## 📈 Key Insights

### Customer Behavior

* Customer demand peaks during lunch and dinner hours.
* Large pizzas are the most frequently ordered size.
* A small number of pizza types account for a large percentage of total sales.

### Revenue Insights

* Revenue is concentrated among a handful of high-performing pizzas.
* Certain pizza categories consistently outperform others.
* Peak sales periods present opportunities for operational optimization.

---

## 💡 Business Recommendations

* Promote top-performing pizzas through targeted marketing campaigns.
* Optimize staffing during peak ordering hours.
* Increase visibility of low-performing products through discounts and bundle offers.
* Expand successful pizza categories with new menu options.
* Build an interactive business dashboard for real-time monitoring.

---

## 📁 Repository Structure

```text
pizza-sales-sql-analysis/
│
├── README.md
│
├── data/
│
├── sql/
│   ├── pizza_sales_analysis.sql
│
├── python/
│   ├── pizza_sales_data_analysis.py
│
│
├── images/
│
├── docs/
│   └── project_report.md
│
└── LICENSE
```

---

## 🚀 Skills Demonstrated

* SQL Querying
* Relational Database Analysis
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Intelligence
* Revenue Analysis
* Git & GitHub

---

## 📜 Project Report

A detailed project report is available in:

```text
docs/project_report.md
```
Google Colab Link - https://colab.research.google.com/drive/1ksFSlAS-PI4_6rOWsZzm-L6CdviQR6pM?usp=sharing 
---

## 👨‍💻 Author

**Samiur Rabbi Alex**

Aspiring AI Engineer | Data Analytics Enthusiast | Machine Learning Learner

Connect with me through GitHub and LinkedIn.
