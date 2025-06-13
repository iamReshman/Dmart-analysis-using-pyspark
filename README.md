# 🛒 Dmart Sales Analysis Using PySpark

This project implements a **data pipeline using Apache Spark (PySpark)** to process, integrate, and analyze sales data from Dmart. It combines data from three sources — customers, products, and sales — and performs transformations and business analysis to generate valuable insights.

---

## 📌 Problem Statement

The goal is to:
- Build a PySpark-based ETL pipeline to load and clean customer, product, and sales data.
- Integrate the datasets using appropriate joins.
- Perform analytical queries to answer key business questions.
- Generate insights to help Dmart optimize its sales strategies.

---

## 🧰 Technologies Used

- Python
- Apache Spark (PySpark)
- Databricks (Windows environment)
- CSV file handling
- Git & GitHub

---

## 🗂️ Dataset Files

- `Customer.csv`: Customer details (ID, Name, Segment, Age, etc.)
- `Product.csv`: Product details (ID, Category, Sub-Category, etc.)
- `Sales.csv`: Sales transactions (Product ID, Customer ID, Quantity, Profit, etc.)

---

## 🚀 How to Run

1. Upload `Customer.csv`, `Product.csv`, and `Sales.csv` to your Databricks workspace.
2. Open or create a new Python notebook or `.py` file.
3. Copy and paste the code from `dmart_pipeline.py` into the notebook.
4. Run the cells to load data, clean it, and execute all queries.

---

## 🔍 Business Questions Answered

1. What is the total sales for each product category?
2. Which customer has made the highest number of purchases?
3. What is the average discount given on sales across all products?
4. How many unique products were sold in each region?
5. What is the total profit generated in each state?
6. Which product sub-category has the highest sales?
7. What is the average age of customers in each segment?
8. How many orders were shipped in each shipping mode?
9. What is the total quantity of products sold in each city?
10. Which customer segment has the highest profit margin?

---

## 📊 Sample Output

> Category: Technology  
> Total Sales: ₹240,000+

> Top Customer ID: C-45673  
> Purchases: 75

---

## 🎯 Key Insights

- Certain sub-categories drive the majority of revenue.
- Specific regions and customer segments show higher profit margins.
- Discounting strategy can be analyzed using average discount data.



