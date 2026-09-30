# ☕ Coffee Shop Sales Analysis | Microsoft Excel

**End-to-end sales analytics project using Microsoft Excel based on Coffee Shop Sales data from New York, covering January–June 2023.**

The project focuses on transforming transactional data into business insights through data profiling, cleaning, KPI analysis, sales performance analysis, product and category evaluation, ABC analysis, and dashboard development.

---

## 📊 Project Overview

The dataset contains **149,116 transactions**, **214,470 items sold**, **80 products**, **9 product categories**, and **3 store locations**.

During the analyzed period, total revenue reached **$698.8K**, with an Average Order Value of **$4.69**.

The analysis was designed to answer key business questions around revenue growth, product performance, category contribution, store performance, transaction basket behavior, and sales patterns over time.

---

## 🧹 Data Preparation

The project started with data profiling and quality validation, including checks for missing values, duplicate transactions, invalid quantities and prices, date and time consistency, ID-to-attribute relationships, text quality, and potential outliers.

The cleaning stage included data type validation, date and time validation, removal of unnecessary spaces from `product_detail` using **TRIM()**, and creation of a calculated **Revenue** field.

Potential outliers were reviewed and retained because they were not automatically identified as data errors.

---

## 📈 Sales & Product Analysis

The analysis covered monthly revenue and transaction trends, category performance, top products, store performance, day-of-week and time-of-day patterns, as well as transaction basket behavior.

Revenue increased by **103.8%** from January to June, while transaction volume increased by **104.2%**. AOV remained almost unchanged at **−0.2%**, indicating that revenue growth was primarily driven by higher transaction volume.

**Coffee and Tea generated 66.74% of total revenue**, while the top 10 products contributed **25.38%**.

Sales were strongly concentrated in the morning, with **55.56% of revenue generated between 06:00 and 11:00** and **10:00 identified as the peak hour**.

Revenue was also distributed almost evenly across **Hell's Kitchen, Astoria, and Lower Manhattan**.

---

## 📦 ABC Product Portfolio Analysis

An **ABC analysis** was conducted to evaluate the contribution of individual products to total revenue.

**42 of 80 products (52.5%) generated 79.25% of total revenue**, while the remaining 38 products generated 20.75%.

This indicates that revenue is distributed across a relatively broad product portfolio rather than being concentrated in a very small group of products.

---

## 📊 Excel Dashboard

The final dashboard provides a visual overview of sales performance, including revenue, transactions, AOV, items sold, revenue growth, monthly trends, category performance, top products, and store contribution.

**Tools used:** Microsoft Excel, Excel Tables, formulas, PivotTables, charts, conditional formatting, and ABC analysis.

---

## 💡 Key Insights

**Revenue growth was volume-driven.** Revenue more than doubled from January to June, primarily due to a significant increase in transaction volume.

**Coffee and Tea are the core revenue categories.** Together, they account for more than two-thirds of total revenue.

**Morning is the key sales window.** More than half of total revenue is generated between 06:00 and 11:00.

**Revenue is distributed across a broad product portfolio.** More than half of the products contribute nearly 80% of total revenue.

---

## ⚠️ Data Limitations

The dataset does not contain cost, expense, customer, or marketing information. Therefore, profitability and margin analysis, customer segmentation, LTV, repeat purchase analysis, and marketing campaign effectiveness could not be assessed.

---

## 📁 Project Structure

```text
coffee-shop-sales-analysis-excel/
│
├── README.md
├── excel/
├── presentation/
└── screenshots/
```

---

## 👩‍💻 Author

**Alona Oleksiienko**  
Data Analyst

**Email:** alona.leontovich@gmail.com
