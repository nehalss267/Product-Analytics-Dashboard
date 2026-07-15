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
| Top_Selling_Products | Identifies the highest-selling products |
| Category_Total_Sales | Calculates total sales by category |
| Top_Rated_Products | Lists products with the highest ratings |
| Category_Avg_Discount | Computes average discount by category |
| Return_Policy_Distribution | Analyzes return policy distribution |
| Low_Stock_Products | Finds products with low inventory |
| Popular_Subcategory | Identifies the most popular subcategories |
| Seller_With_Most_Products | Shows sellers with the highest product count |

---

## Step 3: Power BI Dashboard

The SQL views were imported into **Power BI (Import Mode)** to build an interactive dashboard consisting of four report pages.

---

# 📈 Dashboard Pages

## 🏠 Page 1 – Home

* Project Overview
* Tools & Technologies Used
* Dashboard Navigation

---

## 📊 Page 2 – Sales Overview

### KPI Cards

* Total Products
* Total Units Sold
* Average Price

### Filters

* Main Category
* Subcategory

### Visualizations

* 📌 Top Selling Products (Bar Chart)
* 🍩 Category-wise Total Sales (Donut Chart)
* 📊 Subcategory Popularity (Column Chart)

---

## 💸 Page 3 – Discounts & Ratings

### KPI Cards

* Average Discount (%)
* Average Product Rating

### Filter

* Main Category

### Visualizations

* ⭐ Top Rated Products (Table)
* 📉 Average Discount by Category (Column Chart)

---

## 📦 Page 4 – Sellers & Return Policy

### KPI Card

* Total Sellers

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
* Which product categories contribute the most revenue?
* Which products receive the highest customer ratings?
* Which categories offer the largest discounts?
* Which sellers list the most products?
* Which products are running low on stock?
* How are return policies distributed across products?
* Which subcategories are the most popular?

---

# 📸 Dashboard Preview

> Dashboard screenshots are available in the **Screenshots** folder.

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
