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

# Project Overview

This project analyzes Olist's Brazilian e-commerce data using SQL and Power BI.

The analysis focuses on:

- Revenue and sales trends
- Order volume
- Product category performance
- Average Order Value (AOV)
- Payment methods
- Customer segmentation
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
- What does customer segmentation reveal about customer behavior?

---

# Key Insights

### Sales Performance

Revenue and order volume were analyzed across monthly and quarterly periods to identify changes in Olist's sales performance over time.

### Product Categories

Product categories were compared based on total sales to identify the categories contributing most to Olist's revenue.

### Customer Segmentation

Customers were segmented based on purchasing behavior to identify groups such as New Customers, Loyal Customers, Champions, and At-Risk Customers.

### Payment Behavior

Average Order Value was compared across payment methods to identify differences in purchasing behavior.

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

`sql/02_business_analysis.sql`

---

# Data Quality

Initial data-quality checks were performed before the business analysis, including checks for potential inconsistencies in customer city and state data.

The checks are available in:

`sql/01_data_quality.sql`

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
| DAX | Measures and customer segmentation |
| GitHub | Version control and documentation |

---

# Repository Structure

```text
Brazilian-E-Commerce-Analysis-O-list/
│
├── README.md
│
├── sql/
│   ├── 01_data_quality.sql
│   └── 02_business_analysis.sql
│
├── dashboard/
│   ├── olist_ecommerce_dashboard.pbit
│   └── olist_ecommerce_dashboard.pdf
│
└── images/
    ├── dashboard_page_1.png
    └── dashboard_page_2.png
