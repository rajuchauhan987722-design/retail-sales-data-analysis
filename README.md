# retail-sales-data-analysis
✅ Short Description (Best Option)  End-to-end Retail Sales Data Analysis using Python, Pandas, and Matplotlib with EDA, data cleaning, and business insights visualization.
📊 Retail Sales Analysis (Python)
📌 Project Overview

This project focuses on analyzing retail sales data to extract meaningful business insights.
Using Python, Pandas, and Matplotlib, the dataset was cleaned, processed, and analyzed to understand sales trends, customer behavior, and revenue performance.

🛠️ Tools & Technologies

Python

Pandas

Matplotlib

Jupyter Notebook

📂 Dataset Information

The dataset contains 310 records with the following features:

Order_ID

Order_Date

Customer_Age

Product_Category

Quantity

Price

Payment_Mode

🔎 Project Workflow
1️⃣ Data Understanding

Checked dataset shape, columns, and data types

Used .describe() and .info() for statistical summary

2️⃣ Data Cleaning

Converted Order_Date to datetime format

Filled missing values in:

Customer_Age (median value)

Payment_Mode ("unknown")

Removed duplicate records

3️⃣ Feature Engineering

Created a new column:
Total_Sales = Quantity × Price

Extracted Month from Order_Date for monthly analysis

4️⃣ Exploratory Data Analysis (EDA)

Category-wise total sales

Payment mode-wise revenue

Top 5 highest sales orders

Monthly sales trends

Daily sales trends

Customer age distribution

Price vs Quantity relationship
