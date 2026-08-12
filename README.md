# Brazilian E-Commerce Analysis — Olist

SQL and Power BI analysis of the Brazilian Olist E-Commerce dataset.

The project analyzes sales performance, order trends, product categories, payment methods, and customer behavior.

---

# Dashboard

## Page 1 — Sales Overview

<img src="images/dashboard_page_1.png" alt="Olist Sales Overview" width="100%"/>

---

## Page 2 — Customer & Product Analysis

<img src="images/dashboard_page_2.png" alt="Olist Customer and Product Analysis" width="100%"/>

---

# Key Business Insights

- Critical Retention Gap: Repeat customer rate is just 3.12%, highlighting heavy reliance on new customer acquisition.

- Credit Card Dominance: Credit cards account for 78.34% ($12.54M) of total revenue, followed by Boleto at 17.92% ($2.87M) and Vouchers at 1.36% ($0.22M).

- SP Regional Concentration: São Paulo dominates with 42K customers (15K in SP city alone), generating over triple the customers of second-ranked Rio de Janeiro (13K).

- Weekday Ordering Bias: 77.02% of orders occur on weekdays compared to just 22.98% on weekends.

- Top Product Categories: Top revenue drivers are health_beauty, watches_gifts, and bed_bath_table.

- High Customer Ratings: Average review score stays strong at 4.08/5 across 96.1K customers and 99.4K orders.

- Basket Metrics: Average Order Value stands at $159.33, with an Average Customer Spend of $164.87 across 135K total items sold.

---

# Project Overview

This project analyzes Olist's Brazilian e-commerce data using SQL and Power BI.

The analysis focuses on:

- Revenue and sales trends
- Order volume
- Product category performance
- Average Order Value (AOV)
- Payment methods
- Customer purchasing behavior

### Workflow

Olist Dataset → SQL EDA → Business Analysis → Power BI → DAX → Dashboard

---

# Business Questions

- What is Olist's total revenue?
- How does revenue change over time?
- How many orders were placed?
- Which product categories generate the most sales?
- What is the Average Order Value?
- How does AOV vary by payment method?
- How does AOV vary across product categories?

---

# SQL Analysis

The SQL analysis was performed using MySQL.

### Revenue Analysis

- Total revenue
- Revenue by quarter
- Revenue by month

### Order Analysis

- Total orders
- Orders by month

### Product Analysis

- Sales by product category

### AOV Analysis

- Overall Average Order Value
- AOV by payment type
- AOV by product category

### SQL Techniques

- Multi-table JOINs
- Aggregations
- GROUP BY
- ORDER BY
- Date functions
- CTEs
- KPI calculations
- Data quality checks

The complete analysis is available in:

`sql/business_analysis.sql`

---

# Dataset

The project uses the Brazilian E-Commerce Public Dataset by Olist.

The dataset contains information about:

- Orders
- Customers
- Products
- Sellers
- Payments
- Reviews
- Order items
- Product categories
- Geolocation

The original dataset is not included in this repository.

---

# Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL | SQL analysis and EDA |
| Power BI | Dashboard and visualization |
| DAX | Measures |
| GitHub | Version control and documentation |

---

# Repository Structure

```text
Brazilian-E-Commerce-Analysis-O-list/
│
├── README.md
│
├── sql/
│   └── business_analysis.sql
│
├── dashboard/
│   ├── olist_ecommerce_dashboard.pbit
│   └── olist_ecommerce_dashboard.pdf
│
└── images/
    ├── dashboard_page_1.png
    └── dashboard_page_2.png
