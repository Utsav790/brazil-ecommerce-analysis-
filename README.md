# brazil-ecommerce-analysis-
End-to-end SQL analysis of 100K+ Target Brazil e-commerce orders (2016–2018), uncovering growth trends, seasonality, logistics performance, payment behavior, and actionable business insights.

📊 Target Brazil E-Commerce Data Analysis (SQL) 📌 Overview

This project presents an end-to-end SQL analysis of 100,000+ e-commerce orders from Target’s Brazil operations (2016–2018). The goal is to uncover insights related to order growth, customer behavior, logistics efficiency, freight costs, and payment patterns, and to provide actionable business recommendations.

🧩 Business Problem

As a Data Analyst at Target, the objective is to:

Analyze e-commerce growth and seasonality

Understand customer purchasing behavior

Evaluate delivery performance and freight costs

Study payment and installment trends

Support data-driven decisions for operational improvement

📂 Dataset

The dataset consists of 8 relational CSV files:

customers.csv – customer demographics and location

orders.csv – order lifecycle and timestamps

order_items.csv – product pricing and freight details

payments.csv – payment methods and installments

reviews.csv – customer feedback and ratings

products.csv – product attributes

sellers.csv – seller information

geolocation.csv – geographic mapping data

🛠️ Tools & Technologies

SQL (PostgreSQL / BigQuery compatible)

Joins, CTEs, aggregations

Date & time analysis

Git & GitHub

🔍 Analysis Performed

Data Exploration
Verified schema and data types

Identified order time range (2016–2018)

Analyzed customer distribution across cities and states

Order Trends & Seasonality
Year-over-year growth analysis

Monthly seasonality trends

Time-of-day analysis (Dawn, Morning, Afternoon, Night)

Geographic Insights
Month-on-month order volume by state

Customer concentration across Brazilian states

Economic Impact
Revenue growth comparison between 2017 vs 2018 (Jan–Aug)

State-wise total and average order value

Freight cost contribution to overall order value

Logistics & Delivery Performance
Delivery lead time calculation

Actual vs estimated delivery comparison

Identification of states with fastest and slowest deliveries

Payment Behavior
Month-on-month analysis of payment types

Installment-based purchase behavior

##📈 Key Insights

Orders show strong year-on-year growth, indicating rapid e-commerce adoption

Clear monthly seasonality, with peaks during festive and year-end periods

Most orders are placed during Afternoon and Night

Urban states dominate demand but also face higher logistics pressure

Many orders are delivered earlier than estimated, indicating scope to improve ETA accuracy

Credit cards and installment payments are the most preferred payment methods

##🚀 Business Recommendations

Improve estimated delivery timelines to enhance customer trust

Optimize logistics partners in high-freight states

Run targeted campaigns during peak ordering hours

Expand seller onboarding and warehouse presence in high-growth regions

Promote installment-based offers for higher-value purchases
