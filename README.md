# 📊 Retail Customer Segmentation & Revenue Analytics

This project demonstrates an **end-to-end data analytics workflow**, transforming raw retail transaction data into actionable insights for **revenue optimization, customer segmentation, and strategic decision-making**.

---

## 📌 Project Overview

A retail company aims to better understand customer purchasing behavior across demographics, product categories, and purchase patterns. The objective is to identify key drivers influencing customer decisions and uncover opportunities to improve **customer engagement, retention, and revenue growth**.

> **Business Question:**  
> How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize business strategies?

---

## 📂 Dataset Summary

- **Total Records:** 3,900 transactions  
- **Features:** 18 columns  
- **Data Includes:**
  - Customer demographics (Age, Gender, Location)  
  - Purchase details (Category, Product, Amount, Season)  
  - Behavioral attributes (Discount usage, Subscription status, Purchase frequency, Review rating, Shipping type)  
- **Data Quality:** 37 missing values in review ratings handled using median imputation  

---

## ⚙️ Methodology

### 1️⃣ Data Preparation & Feature Engineering (Python)

- Loaded and explored dataset using **Pandas**
- Cleaned missing values and ensured data consistency  
- Performed feature engineering:
  - Created **age_group** segmentation  
  - Derived **purchase frequency metrics**  
- Standardized column formats for analysis  
- Prepared dataset for database integration  

---

### 2️⃣ Data Analysis (SQL - PostgreSQL)

- Loaded processed dataset into PostgreSQL  
- Executed analytical queries to uncover business insights:
  - Revenue analysis across demographics and segments  
  - Customer segmentation (**New, Returning, Loyal**)  
  - Identification of high-value discount users  
  - Product performance based on ratings and purchase trends  
  - Subscription vs non-subscription revenue comparison  
  - Shipping type impact on purchase behavior  

---

### 3️⃣ Data Visualization (Power BI)

- Built an **interactive dashboard** for business insights  
- Developed key KPIs:
  - Total customers  
  - Average purchase value  
  - Revenue contribution  
  - Customer segmentation distribution  
- Designed visualizations for:
  - Revenue trends and category performance  
  - Customer demographics and behavior  
  - Subscription and retention insights  
- Enabled filters and drill-down features for deeper analysis  

---

## 📊 Key Insights

- **Subscription customers contribute ~45% of total revenue**, making them a major revenue driver  
- Subscribers show **~78% repeat purchase behavior**, indicating strong customer loyalty  
- Customers using **express shipping spend ~12% more per transaction**, representing premium segments  
- Customer segmentation revealed:
  - **50% New customers**
  - **35% Returning customers**
  - **15% Loyal customers**  
  → Strong opportunity to convert new users into repeat buyers  
- High-value customers actively use discounts while maintaining above-average spending  
- Certain product categories consistently receive higher ratings, indicating strong customer preference  
- Female customers generate slightly higher revenue compared to male customers  

---

## 💡 Business Recommendations

- **Promote subscription programs** to increase customer lifetime value  
- **Implement loyalty strategies** to convert new customers into repeat buyers  
- **Optimize discount policies** to balance revenue growth and profitability  
- **Target premium customer segments** (subscribers, express users) with personalized campaigns  
- **Focus marketing efforts on high-performing product categories**  

---

## 🛠️ Tools & Technologies

- **Python:** Pandas, Data Cleaning, Feature Engineering  
- **SQL (PostgreSQL):** Data querying, segmentation, business analysis  
- **Power BI:** Data modeling, DAX, dashboard development  
- **Excel:** Data preparation and validation  

---

## 📌 Conclusion

This project showcases the ability to:

- Perform **data cleaning and transformation using Python**  
- Conduct **structured business analysis using SQL**  
- Build **interactive dashboards in Power BI**  
- Generate **actionable insights for real-world business decisions**  

---
