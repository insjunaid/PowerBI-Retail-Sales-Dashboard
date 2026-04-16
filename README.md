# 🛒📊 Retail Sales Performance Dashboard (Power BI)

## 📌 Project Overview

This project presents an end-to-end **business intelligence solution** built using Power BI to analyze retail sales performance, customer behavior, and product profitability.

The goal is to transform raw transactional data into actionable insights that support data-driven decision-making.

---

## 🎯 Business Objectives

* Analyze overall sales and profitability trends
* Identify high-value customers and customer segments
* Detect loss-making products and pricing inefficiencies
* Evaluate the impact of discounts on profitability
* Understand regional and category-level performance

---

## 📂 Dataset

* **Source:** Sample Superstore Dataset
* **Domain:** Retail / E-commerce
* **Data Includes:**

  * Orders, Customers, Products, Regions
  * Sales, Profit, Discount, Quantity
  * Order & Shipping dates

---

## 🧠 Data Modeling

* Implemented a **Star Schema**

  * **Fact Table:** Orders
  * **Dimension Tables:** Customers, Products, Location
* Created relationships with:

  * Many-to-One cardinality
  * Single-direction filtering

---

## 🧹 Data Preparation

* Cleaned inconsistent date formats
* Created calculated columns:

  * Profit Margin
  * Delivery Days
  * Order Year & Month
* Handled nulls and ensured correct data types

---

## 📊 Key Metrics (DAX)

* Total Sales
* Total Profit
* Profit Margin (%)
* Total Orders
* Average Delivery Days
* Total Customers
* Average Sales per Customer
* Loss Orders

---

## 📈 Dashboard Structure

### 🛒 Page 1: Retail Sales Performance (Executive View)

* KPI Cards: Sales, Profit, Margin, Orders, Delivery Days
* Sales Trend Analysis (Time Series)
* Category-wise Sales Performance
* Delivery Efficiency by Ship Mode
* Interactive slicers (Region, Year, Segment)

---

### 👥 Page 2: Customer Insights

* Average Sales per Customer
* Customer Distribution by Segment
* Top 10 Customers (Revenue Contribution)
* Customer-level performance analysis

---

### 📦 Page 3: Product Performance

* Profit by Sub-Category (identifies loss areas)
* Loss-Making Products Table
* Category-wise Sales Contribution (Donut Chart)
* Discount vs Profit Analysis (Scatter Plot)

---

## 🔄 Navigation & UX Enhancements

* Added **Back Button Navigation** for seamless page switching
* Consistent theme and layout across pages
* Interactive filters and slicers
* Clean and minimal design for executive readability

---

## 🔍 Key Insights

* High discounts are strongly correlated with reduced profitability
* Certain sub-categories consistently generate losses
* A small percentage of customers contribute a large share of revenue
* Delivery performance varies significantly by shipping mode

---

## 💡 Business Recommendations

* Optimize discount strategies to prevent profit leakage
* Focus on high-value customers for targeted marketing
* Re-evaluate pricing of loss-making products
* Improve logistics for high delivery-time segments

---

## 🛠 Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Power Query (ETL)
* Data Modeling (Star Schema)

---

## 🚀 Project Outcome

This project demonstrates the ability to:

* Perform end-to-end data analysis
* Build scalable data models
* Create impactful dashboards
* Deliver actionable business insights

---

## 📎 Author

Junaid Shariff

---
