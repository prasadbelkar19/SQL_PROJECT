# 📊 SQL Project: Customer & Product Sales Reporting

This project focuses on generating analytical SQL reports using a star-schema dataset containing customer, product, and sales data. The goal is to derive insights that are useful for product teams, business analysts, and decision-makers in an e-commerce or retail business environment.

---

## 📁 Files Included

- `12_report_customers.sql` – SQL script analyzing customer behavior, segmentation, and churn indicators  
- `13_report_products.sql` – SQL script analyzing product sales performance, trends, and revenue contribution  
- `gold.dim_customers.csv` – Customer dimension table  
- `gold.dim_products.csv` – Product dimension table  
- `gold.fact_sales.csv` – Sales fact table containing transaction-level data

---

## 🎯 Project Objectives

- Create reusable SQL scripts to generate key product and customer insights  
- Identify top-selling products, customer segments, and revenue trends  
- Use SQL techniques to join, filter, aggregate, and summarize business data  
- Design queries to support dashboards or periodic business reporting

---

## 🧰 Tools & Technologies

- SQL Server
- GitHub for version control
- MS Excel
- Power BI (for future dashboard extensions)

---

## 📚 Dataset Structure

This project uses a star-schema structure:

- **dim_customers**: Customer-level data (ID, location, registration date, etc.)  
- **dim_products**: Product-level data (ID, category, brand, etc.)  
- **fact_sales**: Sales transactions including customer_id, product_id, date, quantity, and price

---

## 🧠 SQL Concepts Used

- INNER and LEFT JOINs for combining dimension and fact tables  
- Aggregation functions: `SUM()`, `AVG()`, `COUNT()`  
- Grouping and filtering using `GROUP BY` and `WHERE`  
- Date-based filtering  
- CASE statements for segmentation logic

---

## 📌 How to Run

1. Load the `.csv` files into your SQL database as tables:  
   - `gold.dim_customers`  
   - `gold.dim_products`  
   - `gold.fact_sales`

2. Run the SQL scripts (`.sql` files) to generate reports

3. Use results in Power BI, Excel, or internal BI tools

---

## ✅ Outcome

This project demonstrates real-world SQL reporting skills including query writing, data modeling, and business insight generation. It can be extended further into dashboarding or advanced analytics.

---

