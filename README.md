📊 Flipkart Sales Analytics
📌 Project Overview

This project is an end-to-end data analytics case study on Flipkart sales data. The objective is to analyze sales, pricing, discounts, customer ratings, payment methods, and return risk to generate meaningful business insights that support data-driven decision-making.

🎯 Business Objective

The project focuses on answering key business questions such as:

How are products distributed across different price bands?
Which products receive the highest discounts?
How do customer ratings vary across products?
Which payment methods contribute the most revenue?
Which product segments have a higher return risk?
🛠️ Tech Stack
Python (Pandas, NumPy) – Data Cleaning & Feature Engineering
MySQL – Data Analysis using SQL
Power BI – Dashboard & Data Visualization
Git & GitHub – Version Control
🧹 Data Cleaning & Feature Engineering

The dataset was cleaned and transformed using Python by:

Converting date columns into datetime format
Handling missing values
Standardizing numerical columns
Creating new analytical features:
discount_amount
price_band
rating_band
return_risk_flag
listing_year
listing_month

The cleaned dataset was then used for SQL analysis and Power BI visualization.

🗄️ SQL Analysis

SQL queries were written to analyze:

Product distribution across price bands
Average selling price and discount trends
Monthly listing trends
Revenue contribution by payment methods
Customer rating distribution
High return-risk product segments


📊 Dashboard

The Power BI dashboard includes:

KPI Cards
Price Band Analysis
Discount Analysis
Monthly Trends
Product Rating Distribution
Payment Mode Analysis
Return Risk Analysis
Interactive Filters & Slicers
🔍 Key Insights
Medium-priced products have the highest number of listings.
Lower-priced products generally offer higher discounts.
Most products receive Average to Good customer ratings.
Revenue is distributed relatively evenly across major payment methods.
Higher return risk is concentrated in specific product segments.


📂 Project Structure
Flipkart-Sales-Analytics/
│
├── Dataset/
│   ├── Raw_Data.csv
│   └── Cleaned_Data.csv
│
├── Python/
│   └── Data_Cleaning.ipynb
│
├── SQL/
│   └── Flipkart_SQL_Analysis.sql
│
├── PowerBI/
│   └── Flipkart_Sales_Dashboard.pbix
│
└── README.md


🚀 Skills Demonstrated
Data Cleaning
Feature Engineering
SQL
Data Analysis
Power BI
Data Visualization
Business Intelligence
Business Insight Generation
Data Storytelling
