# E-Commerce Sales Analysis

**Data Analysis Project | Python · SQL · Power BI**

---

## Project Overview

This project analyzes **34,500 e-commerce transactions** to uncover business insights, track sales performance, and identify growth opportunities. The analysis covers data cleaning, database management, SQL querying, and interactive dashboard development — showcasing a complete data analytics workflow.

---

## Objective

- Clean and preprocess raw e-commerce data using Python
- Store and query data using SQLite
- Extract actionable business insights through 8 analytical SQL queries
- Build an interactive Power BI dashboard for stakeholders

---

## Technologies Used

| Tool | Purpose |
|------|---------|
| **Python (Pandas, NumPy)** | Data cleaning and preprocessing |
| **SQLite** | Database creation and query execution |
| **Power BI** | Interactive dashboard and visualization |
| **GitHub** | Version control and portfolio hosting |

---

## Project Structure
| File | Description |
|------|-------------|
| `cleaned data.ipynb` | Python data cleaning code |
| `mysql queries.ipynb` | 8 SQL analytical queries |
| `ecommerce_cleaned.csv` | Final cleaned dataset (34,500 rows) |
| `ecommerce.db` | SQLite database |
| `e-commerce sales dashboard.pbix` | Power BI dashboard file |
| `sql_results_monthly_trend.csv` | Monthly sales trend results |
| `sql_results_category_sales.csv` | Sales by category results |
| `sql_results_weekday_sales.csv` | Sales by weekday results |
| `sql_results_payment_method.csv` | Sales by payment method results |
| `sql_results_weekday_vs_weekend.csv` | Weekday vs weekend results |
| `sql_results_customer_gender.csv` | Sales by customer gender results |
| `sql_results_growth.csv` | Month-over-month growth results |
| `sql_results_top_customers.csv` | Top 10 customers results |

---

## Data Cleaning Process (Python)

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

## Dashboard KPIs

| Metric | Value |
|--------|-------|
| **Total Sales** | **$5.87M** |
| **Total Orders** | **35,000** |
| **Total Customers** | **8,000** |
| **Average Order Value** | **$170.01** |

---

## Dashboard Visuals

### 1. KPIs (Top Row)
| KPI | Value |
|-----|-------|
| Total Sales | $5.87M |
| Total Orders | 35,000 |
| Total Customers | 8,000 |
| Average Order Value | $170.01 |

---

### 2. Slicers (Filters)
| Slicer | Options |
|--------|---------|
| Category | Beauty, Electronics, Fashion, Grocery, Home, Sports, Toys |
| Year | 2023, 2024, 2025 |
| Payment Method | COD, Credit Card, Debit Card, PayPal, UPI, Wallet |
| Region | Central, East, North, South, West |
| Customer Gender | Female, Male, Other |

---

### 3. Charts

| Chart | Chart Type | Description |
|-------|------------|-------------|
| Total Sales by Year | Line Chart | Sales trend across 2023-2025 |
| Total Sales by Payment Method | Pie Chart | Sales distribution by payment type |
| Total Sales by Weekday | Bar Chart | Sales performance by day of week |
| Sum of Quantity by Category | Bar Chart | Total quantity sold by product category |
| Total Sales by Customer Gender | Pie Chart | Sales distribution by gender |
| Total Sales by Region | Bar Chart | Sales performance by region |
---

## Key Insights

| Insight | Detail |
|---------|--------|
| **Top Category** | Electronics generates highest sales |
| **Top Payment Method** | Credit cards is most used (35.07%) |
| **Top Region** | South region leads in revenue |
| **Top Gender** | Male customers contribute more (48.65%) |
| **Best Day** | Tuesday shows highest sales |

---

## How to Use
1. Use slicers to filter data by category, year, payment method, region, or gender
2. Hover over charts for detailed values
3. Click on any chart element to cross-filter other visuals

---

## Dashboard Preview
<img width="1107" height="621" alt="image" src="https://github.com/user-attachments/assets/c4d15169-6a60-4f49-8e1b-d9207fbbe729" />



