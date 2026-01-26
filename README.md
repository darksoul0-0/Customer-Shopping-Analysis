📌 Project Overview

This project analyzes 3,900 customer transactions to uncover insights into spending patterns, customer segments, product performance, and subscription behavior. The goal is to support data-driven business decisions related to marketing, customer retention, and revenue optimization.

🧰 Tools & Tech Stack

Python: pandas, numpy

SQL: PostgreSQL / MySQL

Power BI: Interactive dashboards & visualization

📊 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics (age, gender, location, subscription status)

Purchase details (item, category, amount, discount, shipping type)

Behavioral metrics (previous purchases, purchase frequency, review rating)

Missing Data: Review Rating column (handled during preprocessing)

🧹 Data Preparation (Python)

Loaded and explored data using pandas

Handled missing values using category-wise median imputation

Standardized column names for consistency

Feature engineering:

Created age_group

Converted purchase frequency into days

Removed redundant columns

Loaded cleaned data into a SQL database for analysis

🧠 Business Analysis (SQL)

Used advanced SQL concepts (CTEs, window functions, aggregations) to answer key questions:

Revenue contribution by gender and age group

Spending behavior of subscribers vs non-subscribers

Top products by average rating and purchase volume

Impact of discounts and shipping type on spending

Customer segmentation into New, Returning, and Loyal groups

Top 3 products within each category

📈 Dashboard (Power BI)

Built an interactive Power BI dashboard connected to the SQL database

Visualized KPIs, trends, and customer segments

Enabled drill-down analysis for business stakeholders

💡 Key Insights

Subscribers show higher average spending and revenue contribution

Certain products rely heavily on discounts, impacting margins

Loyal customers drive a disproportionate share of revenue

Express shipping users tend to have higher purchase values

✅ Outcome

Delivered actionable insights to support:

Marketing strategy

Customer retention programs

Product positioning

Revenue optimization

📁 Project Structure
├── data/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard/
├── README.md

🔍 Notes

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI, aligned with real-world Data Analyst responsibilities.
