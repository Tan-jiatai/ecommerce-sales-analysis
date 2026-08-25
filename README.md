# 🛒 E-Commerce Sales Analysis

**Data Analysis Project | Python · SQL · Power BI**

---

## 📌 Project Overview

This project analyzes **34,500 e-commerce transactions** to uncover business insights, track sales performance, and identify growth opportunities. The analysis covers data cleaning, database management, SQL querying, and interactive dashboard development — showcasing a complete data analytics workflow.

---

## 🎯 Objective

- Clean and preprocess raw e-commerce data using Python
- Store and query data using SQLite
- Extract actionable business insights through 8 analytical SQL queries
- Build an interactive Power BI dashboard for stakeholders

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **Python (Pandas, NumPy)** | Data cleaning and preprocessing |
| **SQLite** | Database creation and query execution |
| **Power BI** | Interactive dashboard and visualization |
| **GitHub** | Version control and portfolio hosting |

---

## 📁 Project Structure
ecommerce-sales-analysis/
│
├── cleaned data.ipynb # Python data cleaning code
├── mysql querries.ipynb # 8 SQL analytical queries
├── ecommerce_cleaned.csv # Final cleaned dataset (34,500 rows)
├── ecommerce.db # SQLite database
├── e-commerce sales dashboard.pbix # Power BI dashboard file
│
├── sql_results_monthly_trend.csv
├── sql_results_category_sales.csv
├── sql_results_weekday_sales.csv
├── sql_results_payment_method.csv
├── sql_results_weekday_vs_weekend.csv
├── sql_results_customer_gender.csv
├── sql_results_growth.csv
└── sql_results_top_customers.csv


---

## 🧹 Data Cleaning Process (Python)

| Step | Action |
|------|--------|
| 1 | Removed duplicate records |
| 2 | Handled missing values (dropna) |
| 3 | Converted `order_date` to datetime format |
| 4 | Extracted: `year`, `month`, `day`, `weekday`, `quarter` |
| 5 | Converted `price`, `total_amount`, `quantity` to numeric |
| 6 | Removed invalid transactions (quantity ≤ 0, total_amount ≤ 0) |
| 7 | Created `unit_price` column (total_amount / quantity) |
| 8 | Reset index and exported cleaned data |

---

## 📊 SQL Analysis (8 Queries)

| # | Query | Purpose |
|---|-------|---------|
| 1 | Monthly Sales Trend | Track sales and order volume over time |
| 2 | Sales by Category | Identify top performing categories |
| 3 | Sales by Weekday | Find best performing days |
| 4 | Sales by Payment Method | Analyze payment preferences |
| 5 | Weekday vs Weekend | Compare weekend and weekday performance |
| 6 | Sales by Customer Gender | Analyze spending by gender |
| 7 | Month-over-Month Growth | Measure revenue growth rate |
| 8 | Top 10 Customers | Identify highest spending customers |

**Key SQL Concepts Used:**
- `GROUP BY` with aggregations
- `COUNT(DISTINCT)` for unique orders
- `CASE WHEN` for conditional grouping
- `LAG()` Window Function for growth calculation
- `ROW_NUMBER()` for ranking
- Common Table Expressions (CTEs)

---

## 📈 Dashboard KPIs

| Metric | Value |
|--------|-------|
| **Total Sales** | **$5.87M** |
| **Total Orders** | **35,000** |
| **Total Customers** | **8,000** |
| **Average Order Value** | **$170.01** |

---

## 📊 Dashboard Visuals

| Visual | Purpose |
|--------|---------|
| Line Chart | Monthly sales trend over time |
| Bar Chart | Sales by product category |
| Pie Chart | Sales distribution by payment method |
| Bar Chart | Sales by customer gender |
| Bar Chart | Sales by region |
| Bar Chart | Sales by weekday |
| Slicers | Filter by category, year, payment method |

---

## 💡 Key Business Insights

| Insight | Business Action |
|---------|-----------------|
| **Electronics** is top category ($2.06M) | Increase inventory and promotions |
| **UPI** is most used payment (48%) | Offer UPI-exclusive discounts |
| **South** region generates highest revenue ($2.79M) | Expand marketing in South region |
| **Q4 (Oct-Dec)** is peak season | Plan holiday campaigns early |
| **Male** customers spend more ($2.79M) | Create male-targeted ads |
| **Tuesday** has highest weekday sales | Run mid-week promotions |

---

## 🖥️ Dashboard Preview
<img width="1117" height="627" alt="image" src="https://github.com/user-attachments/assets/e429148d-49c9-469e-b078-f9eb8af9041c" />



