📊 Customer Behavior Analysis
📌 Project Overview

The Customer Behavior Analysis project focuses on analyzing customer transaction data to uncover patterns in purchasing behavior, preferences, and engagement.
The insights derived from this analysis help businesses make data-driven decisions related to marketing strategies, customer retention, revenue growth, and subscription optimization.

This project combines Python, SQL, and Power BI to perform end-to-end data analysis and visualization.

🧾 Dataset Description

Total Records: 3,900 customer transactions

Total Features: 18

Missing Values:

Review Rating column contains 37 missing values (handled during preprocessing)

Dataset Includes:

Customer Demographics

Age

Gender

Location

Product Details

Item Purchased

Category

Size

Color

Season

Transaction & Sales Data

Purchase Amount (USD)

Payment Method

Shipping Type

Discount Applied

Promo Code Used

Customer Behavior

Previous Purchases

Frequency of Purchases

Subscription Status

Review Rating

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL (Data querying & business analysis)

Power BI (Interactive dashboard)

Jupyter Notebook

Git & GitHub

🔍 Exploratory Data Analysis (EDA)

Performed using Python:

Data Cleaning & Preprocessing

Initial inspection using info() and describe()

Filled missing Review Rating values using median by category

Removed promo_code_used column due to redundancy with discount_applied

Feature Engineering

Categorized ages into:

Young Adult

Adult

Middle-Aged

Senior

Created purchase_frequency_days from purchase frequency data

🧮 Data Analysis Using SQL

Key business questions answered using SQL:

Revenue by Gender

High-Spending Discount Customers

Top 5 Products by Average Review Rating

Shipping Type Comparison (Standard vs Express)

Subscribed vs Non-Subscribed Customers

Discount-Dependent Products

Customer Segmentation

New

Returning

Loyal

Top 3 Products per Category

Repeat Buyers vs Subscription Relationship

Revenue Contribution by Age Group

📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

Customer distribution

Revenue by category, gender, and age group

Subscription vs non-subscription trends

Payment methods and shipping preferences

Discount and promotional impact

💡 Business Recommendations
1️⃣ Subscription Strategy Optimization

Insights

Non-subscribers generate higher total revenue due to volume

Average spend is similar for both groups

Recommendations

Improve subscription value (exclusive deals, free express shipping)

Target high-spending non-subscribers

Introduce tiered subscription plans
