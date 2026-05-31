# 🍕 Pizza Sales Analytics Project

## SQL + Python + Data Visualization

---

# Executive Summary

This project presents an end-to-end sales analytics solution built using SQL, Python, and data visualization techniques. The objective was to analyze pizza sales data to uncover customer purchasing behavior, product performance, revenue trends, and operational insights.

The project combines relational database analysis using SQL with exploratory data analysis (EDA) and visualization using Python, enabling a comprehensive understanding of business performance and data-driven decision-making.

---

# 1. Project Objectives

The primary goals of this project are:

* Analyze overall sales performance.
* Measure total revenue generation.
* Identify top-performing pizza products.
* Understand customer ordering behavior.
* Discover peak business hours.
* Analyze category and size preferences.
* Measure product revenue contribution.
* Generate business recommendations based on data.
* Create visual dashboards and charts for stakeholder reporting.

---

# 2. Technology Stack

| Tool             | Purpose                     |
| ---------------- | --------------------------- |
| MySQL            | Data Storage & SQL Analysis |
| SQL              | Business Query Analysis     |
| Python           | Data Analysis               |
| Pandas           | Data Manipulation           |
| Matplotlib       | Data Visualization          |
| Git & GitHub     | Version Control             |
| Jupyter Notebook | Exploratory Analysis        |

---

# 3. Dataset Overview

The Pizza Sales dataset consists of four relational tables.

## Orders

Stores order-level information.

| Column   |
| -------- |
| order_id |
| date     |
| time     |

---

## Order Details

Stores transaction details.

| Column           |
| ---------------- |
| order_details_id |
| order_id         |
| pizza_id         |
| quantity         |

---

## Pizzas

Stores product pricing and size information.

| Column        |
| ------------- |
| pizza_id      |
| pizza_type_id |
| size          |
| price         |

---

## Pizza Types

Stores pizza metadata.

| Column        |
| ------------- |
| pizza_type_id |
| name          |
| category      |
| ingredients   |

---

# 4. Database Schema

```text
Orders
│
├── Order Details
│
├── Pizzas
│
└── Pizza Types
```

## Relationships

* One Order → Many Order Details
* One Pizza → Many Order Details
* One Pizza Type → Many Pizzas

This relational structure enables efficient analytical queries using JOIN operations.

---

# 5. SQL Analysis

## Basic Business Questions

### Sales Performance

* Total number of orders placed
* Total revenue generated
* Highest-priced pizza

### Customer Preferences

* Most ordered pizza size
* Top 5 most ordered pizza types

---

## Intermediate Analysis

### Product Analysis

* Quantity sold by category
* Category distribution

### Customer Behavior

* Orders by hour
* Average pizzas ordered per day

### Revenue Analysis

* Top 3 pizzas by revenue

---

## Advanced Analysis

### Revenue Contribution

* Percentage contribution by pizza type

### Revenue Trend

* Cumulative revenue over time

---

# 6. Python Exploratory Data Analysis (EDA)

Beyond SQL analysis, Python was used to perform additional business analytics.

## Revenue Analysis

### Revenue by Category

Business Question:

Which pizza category generates the highest revenue?

Visualization:

* Bar Chart
* Pie Chart

---

### Revenue Trend Over Time

Business Question:

How does revenue change throughout the year?

Visualization:

* Time Series Line Chart

---

## Product Performance Analysis

### Top 10 Revenue-Generating Pizzas

Business Question:

Which pizzas contribute the most revenue?

Visualization:

* Horizontal Bar Chart

---

### Top 10 Most Ordered Pizzas

Business Question:

Which pizzas are ordered most frequently?

Visualization:

* Bar Chart

---

## Customer Behavior Analysis

### Orders by Hour

Business Question:

What are the busiest hours of operation?

Visualization:

* Hourly Order Distribution

---

### Orders by Day of Week

Business Question:

Which days generate the most sales?

Visualization:

* Weekly Revenue Chart

---

### Weekend vs Weekday Analysis

Business Question:

Do customers order more on weekends?

Visualization:

* Comparative Bar Chart

---

## Product Preference Analysis

### Pizza Size Distribution

Business Question:

Which pizza size is most popular?

Visualization:

* Bar Chart

---

# 7. Key Insights

## Customer Behavior

### Peak Ordering Hours

Customer demand is concentrated during:

* Lunch hours
* Dinner hours

This suggests staffing and inventory should be optimized around these periods.

---

### Pizza Size Preference

Large-sized pizzas dominate total sales volume, indicating strong customer preference.

---

## Product Insights

### Product Concentration

A small number of pizzas account for a significant percentage of sales and revenue.

This reflects a classic Pareto distribution pattern.

---

### Category Performance

Certain categories consistently outperform others in both quantity sold and revenue generated.

---

## Revenue Insights

### Revenue Drivers

Revenue is concentrated among premium and highly popular pizzas.

### Seasonal Trends

Revenue trends reveal fluctuations that may indicate promotional opportunities or seasonal demand patterns.

---

# 8. Business Recommendations

## Recommendation 1

Focus marketing campaigns on top-selling pizzas.

Expected Impact:

* Increased revenue
* Higher conversion rates

---

## Recommendation 2

Optimize workforce scheduling during peak demand periods.

Expected Impact:

* Reduced waiting times
* Better customer satisfaction

---

## Recommendation 3

Promote low-performing products using:

* Bundle offers
* Discounts
* Seasonal campaigns

Expected Impact:

* Better inventory utilization

---

## Recommendation 4

Expand successful pizza categories.

Expected Impact:

* Increased market demand
* Higher profitability

---

## Recommendation 5

Develop a real-time sales dashboard.

Recommended KPIs:

* Revenue
* Orders
* Average Order Value (AOV)
* Category Revenue
* Product Performance
* Hourly Demand

---

# 9. Future Improvements

Potential future enhancements include:

* Sales forecasting using Prophet
* Revenue prediction using Machine Learning
* Customer segmentation analysis
* Interactive Power BI Dashboard
* Automated reporting pipeline

---

# 10. Conclusion

This project demonstrates practical data analytics skills by combining SQL querying, business intelligence analysis, Python-based exploratory data analysis, and data visualization.

The analysis successfully transformed raw transactional data into actionable business insights, highlighting customer behavior patterns, product performance, revenue drivers, and operational opportunities. The project reflects real-world analytical workflows commonly used by Data Analysts, Business Intelligence Analysts, and Data Scientists.
