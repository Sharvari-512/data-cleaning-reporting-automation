# 📊 Data Cleaning & Reporting Automation (Superstore)

## 🔍 Project Overview
This project focuses on building an **automated data cleaning and reporting pipeline** using a retail (Superstore) dataset.
It demonstrates how raw data can be transformed into **clean, analysis-ready data** and further used to generate **insightful reports and dashboards**.

## 🎯 Objectives
* Automate data cleaning workflows using Python
* Handle missing values, duplicates, and inconsistent formats
* Perform feature engineering for better analysis
* Generate automated visual reports
* Build an interactive dashboard using Power BI

## 🛠️ Tools & Technologies
* Python (Pandas, NumPy, Matplotlib)
* Power BI
* Excel / CSV

## ⚙️ Data Cleaning Steps
* Removed duplicate records
* Handled missing values
* Converted date columns to proper format
* Standardized categorical data (Region, City, etc.)

## 🔧 Feature Engineering
* Delivery Days = Ship Date - Order Date
* Profit Margin (%)
* Month & Year extraction

## 📊 Automated Reports Generated
* Sales by Category
* Profit by Region
* Monthly Sales Trend
All reports are automatically saved in the **output/** folder.

## 📈 Power BI Dashboard
The dashboard is built using the **cleaned dataset** generated from the automation pipeline.

### 🔹 Page 1: Executive Summary
* KPI Cards (Sales, Profit, Orders, Discount)
* Sales & Profit Trend
* Sales by Category
* Profit by Region

### 🔹 Page 2: Business Insights
* Top Products
* Top Customers
* Profit vs Discount Analysis
* Delivery Performance (Histogram)

## 💡 Key Insights
* Technology category generates highest sales
* High discounts negatively impact profit
* Certain regions show lower profitability
* Most deliveries are completed within 2–4 days
