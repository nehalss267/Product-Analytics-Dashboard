# 🛍️ Flipkart Product Analysis Dashboard

**📂 Project Type:** End-to-End Data Analytics Project

---

# 📖 Project Overview

This project showcases a complete **End-to-End Data Analytics Workflow** using a Flipkart product dataset. It demonstrates how raw data can be transformed into meaningful business insights through data cleaning, SQL analysis, and interactive Power BI dashboards.

The project covers:

* 📊 Data Cleaning using Excel
* 🗄️ Data Analysis using PostgreSQL (pgAdmin 4)
* 📈 Interactive Dashboard Development using Power BI

The primary objective is to analyze product performance, sales trends, discounts, seller performance, inventory levels, and return policies to support data-driven business decisions.

---

# 🛠️ Tech Stack

| Tool | Purpose |
| --- | --- |
| **Microsoft Excel** | Data Cleaning & Transformation |
| **PostgreSQL (pgAdmin 4)** | Data Storage, SQL Queries & Views |
| **Power BI** | Data Visualization & Dashboard |

---

# 📊 Workflow

## Step 1: Data Cleaning (Excel)

The raw dataset was downloaded from **Kaggle** and cleaned in Microsoft Excel.

### Cleaning Tasks Performed

* Removed duplicate records
* Fixed inconsistent formatting
* Standardized column names
* Handled missing values where necessary
* Saved the cleaned dataset as a CSV file for SQL import

---

## Step 2: SQL Analysis (PostgreSQL)

The cleaned CSV file was imported into **PostgreSQL** using **pgAdmin 4**.

### Database Table

`flipkart_products`

### SQL Views Created

| View Name | Description |
| --- | --- |
| top_selling_products | Identifies the highest-selling products |
| category_total_sales | Calculates total units sold by category |
| top_rated_products | Lists products with the highest ratings |
| category_avg_discount | Computes average discount by category |
| return_policy_distribution | Analyzes return policy distribution |
| low_stock_products | Finds products with low inventory |
| popular_subcategories | Identifies the most popular subcategories |
| sellers_with_most_products | Shows sellers with the highest product count |

---

## Step 3: Power BI Dashboard

The base `flipkart_products` table and all 8 SQL views were imported into **Power BI (Import Mode)**. Four report pages were built on top of it.

---

# 📈 Dashboard Pages

## 🏠 Page 1 – Home

* Dashboard Title
* Project Description

---

## 📊 Page 2 – Sales Insights

### KPI Cards

* Products
* Units Sold
* Price

### Filters

* Main Category
* Subcategory

### Visualizations

* 🍩 Top Selling Products (Donut Chart)
* 🍩 Category-wise Total Sales (Donut Chart)
* 🗺️ Subcategory Popularity (Treemap)

---

## 💸 Page 3 – Discounts & Ratings

### KPI Cards

* Discount
* Product Rating

### Filters

* Main Category
* Seller

### Visualizations

* ⭐ Top Rated Products (Matrix)
* 📊 Average Discount by Category (Column Chart)
* 📈 Seller Rating vs Units Sold (Line and Stacked Column Combo Chart)

---

## 📦 Page 4 – Inventory & Sellers

### KPI Card

* Sellers

### Filters

* Seller
* Return Policy

### Visualizations

* 📉 Low Stock Products (Bar Chart)
* 🥧 Return Policy Distribution (Pie Chart)
* 📊 Sellers with Most Products (Column Chart)

---

# 📌 Business Insights

The dashboard helps answer important business questions such as:

* Which products generate the highest sales?
* Which product categories sell the most units?
* Which products receive the highest customer ratings?
* Which categories offer the largest discounts?
* Which sellers list the most products?
* Which products are running low on stock?
* How are return policies distributed across products?
* Which subcategories are the most popular?

---

# 📸 Dashboard Preview

> Dashboard screenshots are available in the **Screenshots** folder:
>
> * `1_home.png`
> * `2_Sales Insight.png`
> * `3_Discount and Rating Overview.png`
> * `4_Sellers and Return rate Insights.png`

---

# 🎯 Key Learnings

Through this project, I gained hands-on experience in:

* Cleaning and preparing raw datasets for analysis
* Importing and managing data in PostgreSQL
* Writing analytical SQL queries and creating reusable SQL views
* Designing interactive dashboards in Power BI
* Creating KPIs and business-focused visualizations
* Building a complete end-to-end data analytics project

---
