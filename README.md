# 📊 AtliQ Hardware Sales & Finance Analytics using MySQL

## 📌 Project Overview

This project focuses on solving real-world business analytics problems using MySQL for AtliQ Hardware.

The project simulates business requirements given by product owners and converts them into SQL-based analytical reports. It covers sales analysis, financial reporting, market performance tracking, and advanced SQL reporting workflows using real business scenarios.

The objective of this project is to demonstrate practical SQL skills used in real-world data analytics and business intelligence environments.

---

# 🚀 Business Problems Solved

## ✅ TASK 1 — Monthly Product Sales Report

Generated a monthly product-level sales report for **Croma India** customer for FY-2021.

The report includes:

* Month
* Product Name
* Variant
* Sold Quantity
* Gross Price Per Item
* Total Gross Price

This report helps track product-level sales performance and supports further analytics in Excel.

---

## ✅ TASK 2 — Quarter-wise Product Sales Analysis

Generated individual product sales reports for **Croma India** customer specifically for **Quarter 4 of FY-2021**.

This analysis helps identify quarter-specific product performance trends.

---

## ✅ TASK 3 — Monthly Gross Sales Report

Created an aggregate monthly gross sales report for **Croma India** to analyze customer revenue contribution.

The report includes:

* Month
* Total Gross Sales Amount

This helps business teams monitor customer relationships and revenue generation.

---

## ✅ TASK 4 — Yearly Gross Sales Analysis

Generated a yearly gross sales report for **Croma India** using fiscal year calculations.

The report includes:

* Fiscal Year
* Total Gross Sales Amount

This analysis supports yearly financial performance tracking.

---

## ✅ TASK 5 — Market Badge Classification using Stored Procedure

Built a Stored Procedure to classify markets based on total sold quantity.

### Badge Logic:

* Gold → Total Sold Quantity > 5 Million
* Silver → Otherwise

### Inputs:

* Market
* Fiscal Year

### Output:

* Market Badge

This automation improves market segmentation and reporting efficiency.

---

## ✅ TASK 6 — Top Markets, Products & Customers Analysis

Generated analytical reports for:

* Top Markets by Net Sales
* Top Products by Net Sales
* Top Customers by Net Sales

for a given financial year.

These reports provide a holistic view of financial performance and support business decision-making.

---

## ✅ TASK 7 — Net Sales Percentage Share Analysis

Created a report for **Top 10 Markets by Percentage Net Sales Contribution** for FY-2021.

This analysis helps identify the most revenue-contributing markets globally.

---

## ✅ TASK 8 — Net Sales Contribution using Window Functions

Used SQL Window Functions to calculate net sales contribution percentages across different entities.

Implemented advanced analytical calculations using:

* `SUM() OVER()`
* Partitioning techniques

---

## ✅ TASK 9 — Customer & Regional Sales Analysis

Analyzed:

* Customer-wise Net Sales
* Region-wise Sales Contribution

This report helps compare performance across customers and regions.

---

## ✅ TASK 10 — Top Products by Division

Used `DENSE_RANK()` Window Function to identify top-performing products in each division based on quantity sold.

This analysis supports division-level product performance evaluation.

---

# 🛠 SQL Concepts Used

* SELECT Statements
* Joins
* Aggregate Functions
* GROUP BY
* ORDER BY
* Common Table Expressions (CTEs)
* Window Functions
* Views
* Stored Procedures
* User Defined Functions
* Fiscal Year Functions
* CASE Statements
* Ranking Functions
* Data Aggregation
* Business Reporting Queries

---

# ⚙️ Advanced SQL Features Implemented

## User Defined Functions

* `get_fiscal_year()`
* `get_fiscal_quarter()`

## Stored Procedures

* `get_market_badge()`

## Views

* `net_sales()`

## Window Functions

* `RANK()`
* `DENSE_RANK()`
* `SUM() OVER()`

## CTEs

Used for:

* Net Sales Calculations
* Contribution Analysis
* Ranking Reports
* Financial Reporting

---

# 📈 Insights Generated

* Identified top revenue-generating markets
* Evaluated best-selling products
* Analyzed top customers by net sales
* Compared regional sales contribution
* Automated reusable SQL reporting workflows
* Improved business reporting efficiency

---

# 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

* Advanced SQL Query Writing
* Business Analytics
* Financial Reporting
* Window Functions
* Stored Procedures
* CTEs & Views
* Data Aggregation
* Real-world Sales Analysis
* SQL-based Business Reporting

---
