🛍️ Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using 3,900 transactional records to uncover actionable business insights. The goal is to understand spending patterns, customer segments, product performance, subscription trends, and discount impact to support data-driven decision-making.

📂 Dataset

Records: 3,900 transactions

Features: 18 columns

Key Attributes:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Amount, Season, Size, Color)

Shopping behavior (Discount Applied, Promo Code, Review Rating, Shipping Type, Purchase Frequency)

Data Cleaning:

Handled missing values in Review Rating

Standardized column names

Feature engineering (age groups, purchase frequency in days)

🛠️ Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & EDA

PostgreSQL – SQL-based business analysis

SQL – Analytical queries & segmentation

Power BI – Interactive dashboard & visualization

Gamma – Presentation (PPT) creation

🔎 Project Steps

1️⃣ Data Loading & Cleaning (Python)

Imported dataset using Pandas

Performed EDA (info(), describe(), null checks)

Imputed missing review ratings using median by category

Created new features (age groups, frequency in days)

Ensured data consistency

2️⃣ Database Integration

Connected Python to PostgreSQL

Loaded cleaned dataset into database

Executed SQL queries for structured business analysis

3️⃣ Business Analysis (SQL)

Revenue by gender & age group

Subscribers vs Non-subscribers comparison

High-spending discount users

Top-rated & best-selling products

Customer segmentation (New, Returning, Loyal)

Shipping type purchase comparison

4️⃣ Dashboard Development (Power BI)

Built interactive visual dashboard

KPIs: Total Revenue, Average Purchase, Subscription Impact

Category-wise performance analysis

Customer segment insights

📊 Key Results

Identified high-revenue customer segments

Found top-performing products and categories

Analyzed subscription impact on revenue

Evaluated discount effectiveness

Generated insights for targeted marketing strategies

💡 Business Recommendations

Promote subscription benefits to increase retention

Implement loyalty rewards for repeat buyers

Optimize discount strategies to maintain profit margins

Focus marketing on high-revenue age groups

Highlight top-rated products in campaigns

▶️ How to Run

Clone the repository

Install required Python libraries

pip install pandas numpy sqlalchemy psycopg2


Run the Python script for data cleaning

Import the cleaned dataset into PostgreSQL

Execute SQL queries for analysis

Open the Power BI file to explore the dashboard

📌 Project Outcome

This project demonstrates end-to-end data analytics skills including data cleaning, SQL-based business analysis, visualization, and insight generation — making it a complete portfolio-ready analytics project.
