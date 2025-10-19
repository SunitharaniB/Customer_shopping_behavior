# 🛒 Customer Shopping Behavior Analysis
📘 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The main goal is to uncover insights about spending patterns, customer segments, product preferences, and subscription behavior to support better business decisions.

📂 Dataset

Rows: 3,900 | Columns: 18

Key Features: Customer demographics, product details, purchase amount, discounts, review ratings, and shipping type

Missing Data: 37 values in Review Rating (handled using median imputation)
📎 Dataset Link: Click Here

🧹 Data Preparation (Python)

Loaded and cleaned data using pandas

Handled missing values and standardized column names

Created new features like age_group and purchase_frequency_days

Verified redundancy between discount_applied and promo_code_used

Loaded cleaned data into PostgreSQL for further SQL analysis

🧠 Data Analysis (SQL)

Performed structured SQL queries to answer key business questions:

Total revenue by gender and age group

Top-rated and top-selling products

Subscribers vs. non-subscribers

Shipping type performance (Standard vs. Express)

Discount impact on high-spending customers

Customer segmentation: New, Returning, Loyal

📊 Dashboard (Power BI)

An interactive Power BI dashboard was created to visualize:

Revenue trends by category and age group

Product performance and ratings

Subscription and loyalty insights

Discount and shipping impact on sales

💡 Business Recommendations

Promote exclusive subscriber benefits

Launch loyalty programs for repeat buyers

Balance discount strategies with profit margins

Highlight top-rated products in marketing campaigns

Focus marketing on high-spending customer groups

🛠️ Tools Used

Python, PostgreSQL, Power BI, Excel
