#  Retail Sales Performance Analysis (SQL Project)

Analyzing retail sales performance and profitability to support data-driven business decisions using SQL.

This project uses SQL to explore retail business data and extract insights related to:

✔ Sales performance  
✔ Product profitability  
✔ Customer behavior  
✔ Order & shipping efficiency  
✔ Profit and discount relationships  

The goal is to simulate a real industry analytics workflow and generate meaningful business insights from raw transactional data.

---

##  Table of Contents

- [ Project Overview](#-project-overview)  
- [ Business Objectives](#-business-objectives)  
- [ Database Structure](#-database-structure)
- [ Porject Structure](#-project-structure) 
- [ Sales Performance Analysis](#-sales-performance-analysis)  
- [ Product Analysis](#-product-analysis)  
- [ Customer Analysis](#-customer-analysis)  
- [ Order & Shipping Analysis](#-order--shipping-analysis)  
- [ Profit & Discount Insights](#-profit--discount-insights)  
- [ Tools Used](#-tools-used)  
- [How to Run the Project](#-how-to-run-the-project)  
- [ Key Insights](#-key-insights)  
- [ Future Improvements](#-future-improvements)

---

##  Project Overview

This SQL project analyzes retail order data to answer real-world business questions.  
It helps identify:

- High performing regions  
- Profitable products  
- Customer spending patterns  
- Delivery efficiency  
- Impact of discounting on profit  

The analysis is divided into logical business sections for clarity and decision-making.

---

##  Business Objectives

The project answers the following key questions:

### Sales Performance
- Total sales and profit  
- Yearly and monthly sales trends  
- Revenue by region  
- Least profitable states  

### Product Performance
- Top revenue generating products  
- Most profitable categories  
- Discount patterns  
- Product quantity trends  
- Profit margins  

### Customer Insights
- Top customers by spending  
- Sales by segment  
- Customer distribution by region  
- Loss-making customers  

### Operations & Logistics
- Average delivery time  
- Most used shipping mode  
- Slowest deliveries  

### Profit Strategy
- Discount vs profit relationship  
- Region-wise profit per order  
- Loss generating products  

---

##  Database Structure

The analysis uses relational tables:

### Orders
- order_id
- order_date
- ship_date
- sales
- profit
- discount
- quantity
- ship_mode
- product_id
- customer_id

### Customers
- customer_id
- customer_name
- segment
- region
- state

### Products
- product_id
- product_name
- category
- sub_category

---

##  Sales Performance Analysis

This section evaluates overall business revenue and trends.

Key metrics analyzed:

✔ Total company sales and profit  
✔ Best performing year  
✔ Monthly revenue trend  
✔ Revenue by region  
✔ Lowest profit generating state  

---
## Project Struture
Retail-Sales-SQL-Project
│
├── data/
│   └── retail_sales_data.csv
│
├── scripts/
│   └── sales_analysis.sql
│
├── reports/
│   └── sales_analysis_report.pdf
│
└── README.md

---

##  Product Analysis

Focuses on product profitability and performance.

Key metrics:

✔ Top 10 products by revenue  
✔ Most profitable category  
✔ Highest discount sub-category  
✔ Most sold products  
✔ Category profit margin  

---

##  Customer Analysis

Examines customer contribution and segmentation.


Key insights:

✔ Top 10 customers by spending  
✔ Highest revenue generating segment  
✔ Customer count by region  
✔ Customers causing losses  

---

##  Order & Shipping Analysis

Measures logistics performance.

Key metrics:

✔ Average delivery time  
✔ Most used shipping mode  
✔ Longest delivery orders  

---

##  Profit & Discount Insights

Analyzes financial efficiency and pricing strategy.

Key metrics:

✔ Discount vs profit relationship  
✔ Highest average profit per region  
✔ Loss making products  

---

##  Tools Used

- SQL (MySQL / PostgreSQL compatible)
- Relational database concepts
- Aggregate functions
- Joins
- Grouping & filtering
- Business analytics logic

---

##  How to Run the Project

1. Import dataset into SQL database  
2. Create tables (orders, customers, products)  
3. Run SQL script file  
4. Execute queries section by section  
5. Analyze outputs for insights  

---

##  Key Insights

Examples of insights generated:

✔ Identify best performing regions  
✔ Detect unprofitable products  
✔ Understand customer spending behavior  
✔ Measure delivery performance  
✔ Optimize discount strategy  

---

##  Future Improvements

- Create interactive dashboards (Power BI / Tableau)  
- Add forecasting models  
- Build automated ETL pipeline  
- Implement KPI monitoring  
- Advanced profitability modeling

  ## Author

Aryan Meher  
Aspiring Data Analyst  
Skills: SQL | Power BI | Python | Excel
email:aryanmeher04@gmail.com
