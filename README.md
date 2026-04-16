# 🛒📊 Retail Sales Performance Dashboard (Power BI)

## 📌 Project Overview

This project presents an end-to-end **business intelligence solution** built using Power BI to analyze retail sales performance, customer behavior, and product profitability.

The goal is to transform raw transactional data into actionable insights that support data-driven decision-making.

---
## 📖 Case Study: Improving Retail Profitability

### 🧩 Problem Statement

The business was experiencing inconsistent profitability despite strong sales performance.
Key questions included:

* Which products are driving losses?
* Are discounts impacting profitability?
* Who are the most valuable customers?
* Which areas need optimization?

---

### 🔍 Approach

To address these challenges, an end-to-end analytics workflow was implemented:

* Cleaned and transformed raw transactional data using Power Query
* Built a **star schema data model** for efficient querying
* Created DAX measures to track KPIs such as sales, profit, and margins
* Designed interactive dashboards to analyze trends across customers, products, and regions

---

### 📊 Key Findings

* 📉 High discounts are strongly associated with negative profits
* 📦 Certain sub-categories (e.g., Tables) consistently generate losses
* 🧑 A small group of customers contributes a significant portion of revenue
* 🚚 Delivery performance varies by shipping mode, impacting customer experience

---

### 💡 Business Recommendations

* Reduce excessive discounting on low-margin products
* Focus marketing efforts on high-value customers
* Re-evaluate pricing strategy for loss-making categories
* Optimize logistics for faster delivery in key regions

---

### 📈 Impact

This analysis enables stakeholders to:

* Identify profit leakages
* Improve pricing and discount strategies
* Make data-driven decisions for growth

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

  <img width="600" height="500" alt="Image" src="https://github.com/user-attachments/assets/9d4bbabd-6a0d-45dd-b3c1-3d6c4c283065" />

---

### 👥 Page 2: Customer Insights

* Average Sales per Customer
* Customer Distribution by Segment
* Top 10 Customers (Revenue Contribution)
* Customer-level performance analysis

<img width="600" height="500" alt="Image" src="https://github.com/user-attachments/assets/2f7ba2cf-967d-49c1-bf61-00a086d916b6" />
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
