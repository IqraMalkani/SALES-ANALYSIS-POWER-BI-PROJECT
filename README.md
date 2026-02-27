# 📊 Sales Management Dashboard: Power BI & SQL Portfolio Project
## 🔎 Project Overview

This project focuses on building an Executive Sales Management Dashboard designed to support Sales Managers and Sales Representatives with data-driven decision-making.

The objective was to transform raw sales data into a structured data model and deliver an interactive Power BI dashboard that provides clear insights into:

1) Internet sales performance

2) Customer purchasing behavior

3) Product performance

4) Sales vs Budget comparison

5) Sales trends over time

The solution combines SQL for data cleansing and transformation with Power BI for data modeling, DAX calculations, and visualization.

## 🎯 Business Requirement

The business requested an executive-level sales report that:

1) Provides a high-level overview of internet sales

2) Tracks performance against budget

3) Enables detailed customer-level analysis

4) Enables product-level performance analysis

5) Refreshes daily to ensure up-to-date insights

## 👥 User Stories

### Sales Manager

1) Needs a dashboard overview of internet sales

2) Wants to monitor KPIs and compare sales against budget

3) Requires trend analysis over time

### Sales Representative

1) Needs detailed customer-level sales insights

2)Wants to identify high-value customers

3) Needs product-level performance tracking

## 🛠 Technical Implementation
### 🔹 Data Source

SQL Server Database: AdventureWorksDW2019

Budget data: Excel

### 🔹 Data Processing (SQL)

Data was extracted, cleaned, and transformed using SQL:

1) Created dimension tables (Calendar, Customers, Products)

2) Extracted fact table (Internet Sales)

3) Filtered dataset dynamically to include only the last two years

4) Standardized fields and renamed columns for business readability

5) Joined supporting tables (Geography, Product Category, Subcategory)

### 🔹 Data Model

A structured star schema model was implemented in Power BI:

FACT_InternetSales

FACT_Budget

DIM_Calendar

DIM_Customers

DIM_Products

Relationships were defined using proper 1-to-many cardinality for optimized analytical performance.

## 📈 Dashboard Features

The final report includes:

### 1️⃣ Executive Overview Page

Total Sales KPI

Sales vs Budget comparison

Sales Trend over time

High-level performance indicators

### 2️⃣ Customer Analysis Page

Sales per customer

Top-performing customers

Drill-down capability

### 3️⃣ Product Analysis Page

Sales per product

Category & subcategory performance

Product trend analysis

## 💡 Key Skills Demonstrated

1) SQL Data Extraction & Transformation

2) Data Cleansing & Modeling

3) Star Schema Design

4) Power BI Data Modeling

5) DAX Calculations

6) KPI Development

7) Business Requirement Translation

8) Executive Dashboard Design

## 🚀 Project Outcome

This project demonstrates the ability to:

Translate business requirements into analytical solutions

Build scalable data models

Deliver executive-ready dashboards

Combine SQL and Power BI in an end-to-end analytics workflow

## Dashboard

You can view the sales analysis dashboard here:  
[Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjJlMjhjMDUtMmFiYS00ZmZlLTlhYmMtMDYzZTIzMTYwMTUxIiwidCI6ImYwZTZkMmNhLTg3MjgtNDgxMy1hYTI4LTM2MmM4NmNmMjBlNSJ9)

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi, I’m Iqra Malkani. I’m passionate about working with data and building projects across SQL, Power BI and Excel. I focus on creating practical solutions that turn data into meaningful insights and showcase skills that are valuable for business and analytics roles.

You can explore more of my work on my website: www.iqramalkani.com

