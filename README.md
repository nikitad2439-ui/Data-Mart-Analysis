# Data-Mart-Analysis

## 📌 Project Overview
This project analyzes the **sales performance of Data Mart** using SQL.  
The goal is to measure the business impact of **sustainable packaging changes** introduced in June 2020 by cleaning, transforming, and exploring sales data.

---

## 🗂️ Dataset Schema: `weekly_sales`

| Column       | Description                              |
|--------------|------------------------------------------|
| week_date    | Starting date of the week                |
| region       | Business region                          |
| platform     | Sales channel (Retail / Shopify)         |
| segment      | Customer segment                         |
| customer     | Customer identifier                      |
| transactions | Number of transactions                   |
| sales        | Total sales amount                       |

---

## 🔧 Key Steps
### 1. Data Cleansing
- Added **week_number**, **month_number**, and **calendar_year** columns  
- Derived **age_band** and **demographic** columns from segment codes  
- Replaced null values with `"unknown"`  
- Calculated **avg_transaction** = `sales / transactions`  

### 2. Data Exploration
- Identified missing week numbers  
- Total transactions by year  
- Regional monthly sales  
- Transactions by platform (Retail vs Shopify)  
- Sales mix by demographic and age group  

🎓 Learning Outcomes

Proficiency in SQL data cleaning & transformation,
Creating a Data Mart schema for analytics, 
Answering real-world business questions with SQL
