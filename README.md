# Customer Shopping Behavior Analysis

## Project Overview

Customer Shopping Behavior Analysis is an end-to-end data analytics project that explores purchasing patterns, customer demographics, product performance, and subscription behavior using transactional retail data. The project combines Python for data preprocessing, PostgreSQL for business analysis, and Power BI for interactive dashboard visualization to generate actionable business insights.

---

## Problem Statement

Retail businesses generate large volumes of transactional data, but extracting meaningful insights from this data is challenging. This project aims to analyze customer shopping behavior to answer key business questions regarding customer spending, product demand, subscriptions, discounts, and customer segmentation.

---

## Objectives

- Analyze customer purchasing behavior
- Identify top-performing products
- Study customer demographics and spending patterns
- Evaluate subscription performance
- Measure the impact of discounts on sales
- Segment customers based on purchase history
- Build an interactive Power BI dashboard for business decision-making

---

## Dataset Information

| Attribute | Value |
|----------|--------|
| Total Records | 3,900 |
| Features | 18 |
| Missing Values | 37 (Review Rating) |

### Dataset Features

- Customer ID
- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Season
- Color
- Size
- Shipping Type
- Discount Applied
- Promo Code Used
- Review Rating
- Previous Purchases
- Frequency of Purchases

---

## Tech Stack

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI
- Git
- GitHub

---

## Project Workflow

### 1. Data Cleaning (Python)

- Imported dataset using Pandas
- Performed exploratory data analysis
- Checked missing values
- Imputed missing Review Ratings using category-wise median
- Renamed columns using snake_case
- Removed redundant columns
- Created new engineered features:
  - Age Group
  - Purchase Frequency (Days)
- Loaded cleaned dataset into PostgreSQL

---

### 2. SQL Business Analysis

Performed analytical SQL queries to answer business questions:

- Revenue by Gender
- High Spending Customers using Discounts
- Top Rated Products
- Shipping Type Performance
- Subscriber vs Non-Subscriber Revenue
- Discount Dependent Products
- Customer Segmentation
- Top Products in Each Category
- Repeat Buyer Analysis
- Revenue Contribution by Age Group

---

### 3. Power BI Dashboard

Built an interactive dashboard containing:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Revenue by Age Group
- Sales by Category
- Subscription Distribution
- Interactive Filters

Dashboard filters include:

- Gender
- Subscription Status
- Category
- Shipping Type

---

## Key Business Insights

### Customer Insights

- Majority of customers are non-subscribers.
- Loyal customers contribute the largest share of purchases.
- Repeat buyers are more likely to subscribe.

### Sales Insights

- Clothing category generates the highest revenue.
- Express shipping customers spend slightly more than Standard shipping customers.
- Certain products heavily depend on discounts for sales.

### Product Insights

Top-rated products include:

- Gloves
- Sandals
- Boots
- Hat
- Skirt

Most purchased products vary across each category.

---

## Business Recommendations

- Increase subscription benefits to improve customer retention.
- Introduce loyalty rewards for repeat customers.
- Optimize discount strategies to protect profit margins.
- Promote high-rated products in marketing campaigns.
- Target high-revenue age groups with personalized offers.

---

## Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_data.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── feature_engineering.ipynb
│   └── eda.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── Customer_Insights_Dashboard.pbix
│
├── Images/
│   ├── dashboard.png
│   └── preview.png
│
├── README.md
└── requirements.txt
```

---

## Dashboard Preview

> Add your Power BI dashboard screenshot here.

```
Images/dashboard.png
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Query Optimization
- PostgreSQL
- Business Analytics
- Data Visualization
- Power BI Dashboard Design
- Data Storytelling

---

## Future Improvements

- Customer Lifetime Value (CLV) Prediction
- Customer Churn Prediction
- Product Recommendation System
- Sales Forecasting
- Interactive Web Dashboard using Streamlit

---

## Author

**Ravicharan Yerram**

B.Tech | IIT Delhi

- GitHub: https://github.com/ravicharan1819
- LinkedIn: https:linkedin.com/in/ravi-charan-yerram-669691319

---

## License

This project is intended for educational and portfolio purposes.
