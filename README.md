📊 Retail Customer Segmentation & Revenue Analytics

This project demonstrates an end-to-end data analytics workflow, focused on analyzing customer purchasing behavior to uncover actionable business insights. The objective is to transform raw transactional data into meaningful intelligence that supports revenue optimization, customer segmentation, and strategic decision-making.

📌 Business Problem

A retail company aims to better understand customer purchasing behavior across demographics, product categories, and channels. The goal is to identify:

Key drivers of customer spending
High-value customer segments
Impact of discounts, subscriptions, and shipping preferences
Opportunities to improve retention and revenue
🎯 Objective

To analyze customer transaction data and answer:

How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize business strategies?

📂 Dataset Overview
Total Records: 3,900 transactions
Features: 18 columns
Data Includes:
Customer demographics (Age, Gender, Location)
Purchase details (Category, Product, Amount, Season)
Behavioral attributes (Discount usage, Subscription status, Purchase frequency, Review rating, Shipping type)
⚙️ Project Workflow
1️⃣ Data Preparation & Feature Engineering (Python)
Loaded and explored dataset using Pandas
Handled missing values (review ratings imputed using median)
Standardized column formats for consistency
Created new features:
age_group for segmentation
purchase_frequency for behavioral analysis
Ensured data quality and consistency before analysis
2️⃣ Data Analysis (SQL)
Loaded cleaned dataset into PostgreSQL
Performed structured analysis using SQL queries:
Revenue analysis by customer demographics
Identification of high-spending discount users
Product performance based on ratings
Shipping type impact on purchase behavior
Subscription vs non-subscription revenue comparison
Customer segmentation (New, Returning, Loyal)
Repeat purchase behavior and loyalty trends
3️⃣ Data Visualization (Power BI)
Built an interactive dashboard to present insights
Developed key KPIs:
Total customers
Average purchase value
Customer segmentation distribution
Designed visualizations:
Revenue by category and age group
Customer distribution by subscription status
Sales trends and product performance
Enabled filters and drill-down analysis for deeper insights
📊 Key Insights
Subscription customers contribute ~45% of total revenue and show higher retention
Express shipping users spend ~12% more per transaction, indicating premium behavior
Discounts attract high-value customers who still maintain above-average spending
Clear segmentation into New, Returning, and Loyal customers enables targeted engagement
Certain product categories consistently receive higher ratings, indicating strong customer preference
💡 Business Recommendations
Promote subscription programs to increase customer lifetime value
Implement loyalty programs to convert new customers into repeat buyers
Optimize discount strategies to balance revenue and profitability
Focus on high-performing product categories in marketing campaigns
Target premium segments (e.g., express shipping users) with personalized offers
🛠️ Tools & Technologies
Python: Pandas, Data Cleaning, Feature Engineering
SQL (PostgreSQL): Data querying, segmentation, business analysis
Power BI: Data modeling, DAX, dashboard development
Excel: Data preparation and validation


🚀 Key Highlights
End-to-end analytics pipeline (Python → SQL → Power BI)
Strong focus on business-driven insights, not just visualization
Customer segmentation and behavioral analysis
Real-world retail analytics use case
📌 Conclusion

This project showcases the ability to:

Translate raw data into actionable insights
Apply analytical thinking across tools
Build business-oriented dashboards
Communicate findings effectively for decision-making
