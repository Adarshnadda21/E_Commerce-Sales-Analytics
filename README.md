# 🛒 E-commerce Sales Analytics

A MySQL-based Business Analytics project that analyzes e-commerce sales data and generates actionable business insights.

## 📌 Project Overview

This project analyzes customers, orders, products, and sales revenue using SQL.

The analysis focuses on:

- Customer revenue and purchasing behavior
- Product performance
- Product-type revenue
- Monthly revenue trends
- Customer segmentation
- Order analysis
- Revenue growth and rankings

## 🛠️ SQL Skills Used

- Joins
- CTEs
- Subqueries
- Aggregate Functions
- Window Functions
- `ROW_NUMBER()`
- `DENSE_RANK()`
- `LAG()`
- Date Functions
- `GROUP BY` & `HAVING`

## 📊 Key Analysis

| Analysis | SQL Concept |
|---|---|
| Customer Revenue | Joins & Aggregations |
| Product Performance | Aggregations |
| Customers With No Orders | LEFT JOIN |
| Products Never Ordered | LEFT JOIN |
| Customer Ranking | DENSE_RANK() |
| Top Products by Type | ROW_NUMBER() |
| Running Revenue | Window Functions |
| Order Sequence | ROW_NUMBER() |
| Days Between Orders | LAG() |
| Revenue Growth | LAG() |
| Customer Segmentation | CTE & CASE |
| Top Customers by Month | CTE & ROW_NUMBER() |

## 🗂️ Database Tables

- `customers`
- `orders`
- `product_orders`
- `products`

## 💡 Business Insights

The analysis helps identify:

- High-value customers
- Strong and weak-performing products
- Product types generating revenue
- Customers without orders
- Monthly revenue patterns
- Repeat purchasing behavior
- Revenue contribution by orders

## 🎯 Project Goal

To transform raw e-commerce transaction data into meaningful business insights using MySQL.

## 👨‍💻 Tools

**Database:** MySQL  
**Analysis:** SQL  
**Project Type:** Business Analytics / SQL Portfolio Project
