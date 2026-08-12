# Brazilian-E-Commerce-Analysis-O-list-
Olist E-Commerce Sales Analysis
Overview

This project analyzes the Brazilian Olist e-commerce dataset to understand sales performance, order trends, product category performance, payment behavior, and customer purchasing patterns.

The project combines SQL exploratory data analysis with an interactive Power BI dashboard to transform raw e-commerce data into business-focused insights.

Business Questions

The analysis focuses on questions such as:

What is Olist's total revenue?
How does revenue change over time?
How many orders were placed?
Which product categories generate the most sales?
What is the average order value (AOV)?
How does AOV vary by payment method?
How does order value vary across product categories?
What patterns can be identified in customer purchasing behavior?
Dataset

The project uses the Olist Brazilian E-Commerce dataset, which contains information about orders, customers, products, sellers, payments, reviews, and deliveries.

The dataset consists of multiple related tables connected through identifiers such as order_id, customer_id, product_id, and seller_id.

The original dataset is not included in this repository.

Tools & Technologies
SQL — Data exploration, aggregation, joins, and business analysis
MySQL — SQL environment
Power BI — Interactive dashboard and visualization
DAX — Measures and customer segmentation
Git/GitHub — Project version control and documentation
Project Structure
olist-ecommerce-analysis/
│
├── README.md
│
├── sql/
│   ├── 01_data_quality.sql
│   ├── 02_business_analysis.sql
│   └── 03_customer_analysis.sql
│
├── dashboard/
│   ├── olist_dashboard.pbix
│   └── dashboard_preview.png
│
├── images/
│   ├── dashboard_page_1.png
│   └── dashboard_page_2.png
│
└── data/
    └── README.md
SQL Analysis

The SQL analysis covers:

Sales Performance
Total revenue
Revenue by month
Revenue by quarter
Total number of orders
Monthly order volume
Product Analysis
Sales by product category
Comparison of category performance
Customer & Payment Analysis
Average order value
AOV by payment method
AOV by product category
Customer purchasing behavior

The SQL scripts demonstrate the use of:

JOIN
WHERE
GROUP BY
ORDER BY
Aggregate functions
Date functions
CTEs
Multi-table analysis
Power BI Dashboard

The Power BI dashboard presents the main findings from the analysis through two pages.

Page 1 — Sales Overview

Focuses on overall business performance, including:

Revenue
Orders
Average order value
Revenue trends
Order trends
Product category performance




Page 2 — Customer & Product Analysis

Focuses on:

Customer segmentation
Customer purchasing behavior
Product/category performance
Payment behavior
Additional business KPIs




Key Insights

The analysis identified several patterns in Olist's sales and customer data.

Examples include:

Revenue varies significantly across months and quarters.
A relatively small number of product categories account for a large proportion of sales.
Payment methods show differences in average order value.
Customer segmentation reveals differences in customer retention and purchasing behavior.

The exact findings and supporting metrics are presented in the Power BI dashboard.

Skills Demonstrated
SQL
Relational data analysis
Multi-table joins
Aggregations
Date-based analysis
CTEs
Data quality checks
Business KPI calculations
Power BI
Data modeling
DAX measures
KPI cards
Time-series analysis
Category analysis
Customer segmentation
Dashboard design
Analytics
Translating business questions into analytical queries
Identifying trends and patterns
Presenting analytical results to a business audience
How to Reproduce
Download the Olist Brazilian E-Commerce dataset.
Import the tables into MySQL.
Run the SQL scripts in the sql/ directory.
Open the Power BI file in the dashboard/ directory.
Update the data source connection if required.
Conclusion

This project demonstrates an end-to-end analytical workflow using SQL and Power BI, from exploring relational e-commerce data and answering business questions to presenting the results through an interactive dashboard.
