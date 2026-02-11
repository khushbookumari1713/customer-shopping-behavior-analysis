# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This is an end-to-end data analysis project analyzing 3,900 customer transactions to uncover insights into spending behavior, subscription trends, product performance, and customer segmentation.

The project integrates:
- Python (Data Cleaning & EDA)
- PostgreSQL (Business SQL Analysis)
- Power BI (Interactive Dashboard)
- Business Presentation & Report

---

## 📊 Dataset Information
- Records: 3,900
- Features: 18
- Missing Values: 37 in review_rating (handled using median per category)

---

## 🐍 Python - Data Cleaning & Feature Engineering
- Loaded dataset using pandas
- Checked structure using df.info() and df.describe()
- Handled missing review_rating values
- Converted column names to snake_case
- Created age_group feature
- Created purchase_frequency_days feature
- Removed redundant promo_code_used column
- Exported cleaned data to PostgreSQL

---

## 🗄️ SQL - Business Analysis
Performed SQL analysis to answer key business questions:

1. Revenue by Gender
2. High-Spending Discount Users
3. Top 5 Rated Products
4. Shipping Type Comparison
5. Subscribers vs Non-Subscribers Revenue
6. Discount-Dependent Products
7. Customer Segmentation (New, Returning, Loyal)
8. Top 3 Products per Category
9. Repeat Buyers & Subscription Relationship
10. Revenue by Age Group

---

## 📊 Power BI Dashboard
An interactive Power BI dashboard was built to visualize:
- Revenue KPIs
- Customer Segmentation
- Subscription Comparison
- Product Performance
- Discount Impact
- Age Group Revenue

---

## 📑 Presentation & Report
- Business Presentation (PPT)
- Detailed Project Report (PDF)

---

## 💡 Key Business Insights
- Subscribers generate higher average revenue.
- Loyal customers contribute consistent revenue.
- Some products heavily depend on discounts.
- Express shipping customers spend more.
- Certain age groups contribute significantly to revenue.

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- PostgreSQL
- Power BI
- Jupyter Notebook

---

## 🎯 Project Outcome
This project demonstrates:
- Data Cleaning
- Feature Engineering
- SQL Business Analysis
- Dashboard Creation
- Business Insight Generation
- End-to-End Analytics Workflow
