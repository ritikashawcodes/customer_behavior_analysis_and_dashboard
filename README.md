# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover insights into spending patterns, customer segmentation, product preferences, and subscription behavior to support data-driven business decisions.

---

## 📊 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18

### Key Features:

* **Customer Demographics:** Age, Gender, Location, Subscription Status

* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color

* **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

* **Missing Data:** 37 values in `review_rating`

---

## 🐍 Exploratory Data Analysis (Python)

### Data Preparation & Cleaning:

* Loaded dataset using **pandas**
* Used `df.info()` and `describe()` for initial exploration
* Handled missing values in `review_rating` using **median per product category**
* Standardized column names to **snake_case**

### Feature Engineering:

* Created `age_group` for customer segmentation
* Derived `purchase_frequency_days`
* Removed redundant column `promo_code_used`

### Database Integration:

* Connected Python to **PostgreSQL**
* Loaded cleaned dataset into database for SQL-based analysis

---

## 🧠 Data Analysis (SQL)

Key business questions answered:

1. Revenue comparison by gender
2. High-spending customers using discounts
3. Top 5 highest-rated products
4. Average purchase by shipping type
5. Subscribers vs non-subscribers revenue analysis
6. Discount-heavy products identification
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Relationship between repeat buyers and subscriptions
10. Revenue contribution by age group

---

## 📈 Dashboard (Power BI)

An interactive dashboard was built to visualize:

* Revenue trends
* Customer segments
* Product performance
* Purchase behavior patterns

---

## 💡 Business Recommendations

* Improve subscription offerings to increase retention
* Introduce loyalty programs for repeat customers
* Optimize discount strategies to protect margins
* Promote top-rated and high-performing products
* Target high-value customer segments with focused marketing

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy)
* **SQL (PostgreSQL)**
* **Power BI**
* **Data Cleaning & EDA**

---

## 🚀 Outcome

This project demonstrates end-to-end data analysis — from raw data cleaning to business insights and dashboard storytelling — aligning closely with real-world data analyst responsibilities.
