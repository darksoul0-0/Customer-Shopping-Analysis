# 🛍️ Customer Shopping Behavior Analysis

<p align="center">
  <b>Turning 3,900 customer transactions into actionable business insights.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-Business%20Analysis-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
</p>

---

## 📌 About the Project

**Customer Shopping Behavior Analysis** is an end-to-end data analytics project that explores **3,900 customer transactions** to understand purchasing patterns, customer segments, product performance, subscription behavior, and revenue drivers.

The project transforms raw customer transaction data into meaningful business insights using:

**Python → Data Cleaning & Feature Engineering → SQL Analysis → Power BI Visualization**

The ultimate goal is to help businesses make better decisions around **marketing, customer retention, product strategy, and revenue optimization**.

---

## 🎯 Business Objectives

This analysis focuses on answering questions such as:

* 💰 Which customer groups contribute the most revenue?
* 👥 How does spending differ across customer segments?
* 🛒 Which products and categories perform best?
* ⭐ Which products receive the highest ratings?
* 🎟️ How do discounts affect customer spending?
* 🚚 Does shipping type influence purchase value?
* 🔄 How do loyal, returning, and new customers behave?
* 💳 How does subscription status affect purchasing behavior?
* 📈 Which customer segments represent the greatest business opportunity?

---

## 🧰 Tech Stack

| Technology              | Purpose                                            |
| ----------------------- | -------------------------------------------------- |
| 🐍 **Python**           | Data cleaning, preprocessing & feature engineering |
| 🐼 **Pandas**           | Data manipulation and analysis                     |
| 🔢 **NumPy**            | Numerical operations                               |
| 🗄️ **SQL**             | Business analysis and analytical queries           |
| 📊 **Power BI**         | Interactive dashboard and data visualization       |
| 📓 **Jupyter Notebook** | Exploratory data analysis                          |

---

## 📊 Dataset Overview

The dataset contains **3,900 customer purchase records** and **18 features** covering customer demographics, purchasing behavior, products, and transaction details.

### Key Data Categories

**👤 Customer Information**

* Customer ID
* Age
* Gender
* Location
* Subscription Status

**🛍️ Purchase Information**

* Item Purchased
* Category
* Purchase Amount
* Size
* Color
* Season

**📦 Shopping Behavior**

* Previous Purchases
* Purchase Frequency
* Shipping Type
* Discount Applied
* Review Rating

### Dataset Statistics

| Metric             |                      Value |
| ------------------ | -------------------------: |
| Total Transactions |                  **3,900** |
| Total Features     |                     **18** |
| Missing Values     |                     **37** |
| Primary Analysis   | Customer Shopping Behavior |

---

## 🔄 Project Workflow

```text
                 ┌─────────────────────┐
                 │   Raw Transaction   │
                 │        Data         │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Python / Pandas     │
                 │ Data Cleaning       │
                 │ & Preprocessing     │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Feature Engineering │
                 │ & EDA               │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │       SQL           │
                 │ Business Analysis   │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │     Power BI        │
                 │ Interactive         │
                 │ Dashboard           │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Business Insights   │
                 │ & Recommendations   │
                 └─────────────────────┘
```

---

## 🧹 1. Data Cleaning & Preparation

Python was used to prepare the dataset for analysis.

### Key Steps

* Loaded and explored the raw dataset using **Pandas**
* Checked data types and statistical summaries
* Identified and handled missing values
* Applied **category-wise median imputation** for missing review ratings
* Standardized column names
* Removed redundant columns
* Created meaningful derived features
* Converted purchase frequency into a more analysis-friendly format
* Created customer **age groups**
* Prepared the cleaned dataset for SQL analysis

---

## 🧠 2. SQL Business Analysis

SQL was used to answer real-world business questions and uncover patterns that are difficult to identify from raw data alone.

### Analysis Areas

📊 **Revenue Analysis**

* Revenue contribution by gender
* Revenue contribution by age group
* Customer segment revenue

👥 **Customer Analysis**

* New vs Returning vs Loyal customers
* Customer purchasing behavior
* Subscription vs non-subscription behavior

🛍️ **Product Analysis**

* Top-selling products
* Highest-rated products
* Top products within each category

🎟️ **Discount Analysis**

* Discount dependency
* Relationship between discounts and purchase value

🚚 **Shipping Analysis**

* Purchase behavior by shipping type
* Average purchase value across shipping methods

### SQL Techniques Used

* `GROUP BY`
* Aggregate functions
* `CASE WHEN`
* Common Table Expressions (**CTEs**)
* Window functions
* Ranking
* Subqueries
* Customer segmentation

---

## 📈 3. Power BI Dashboard

The cleaned and analyzed data was transformed into an interactive **Power BI dashboard**.

### Dashboard Highlights

* 💰 Revenue KPIs
* 🛒 Product & category performance
* 👥 Customer segmentation
* 📊 Revenue by demographic groups
* 🔄 Subscription analysis
* ⭐ Average rating analysis
* 🚚 Shipping performance
* 🎟️ Discount behavior
* 🔎 Interactive filtering and drill-down analysis

> The dashboard is designed to help business stakeholders quickly move from **high-level KPIs → customer behavior → actionable insights**.

---

## 💡 Key Insights

The analysis revealed several important business patterns:

### 👥 Customer Loyalty

**Loyal customers contribute a disproportionate share of revenue**, making retention strategies especially valuable.

### 💳 Subscription Behavior

Subscribers demonstrate stronger spending and revenue contribution, highlighting an opportunity to improve subscription conversion.

### 🎟️ Discount Dependency

Some products show a strong dependency on discounts, which can create potential pressure on profit margins.

### 🚚 Shipping

Customers selecting **express shipping** tend to have higher purchase values.

### 🛍️ Product Performance

Product-level analysis helps identify high-performing products and opportunities for better inventory and promotional planning.

---

## 📌 Business Recommendations

Based on the analysis, businesses could:

### 1. 🎯 Strengthen Customer Retention

Create loyalty rewards and personalized offers for high-value customers.

### 2. 💳 Increase Subscription Conversions

Use targeted campaigns to convert frequent and high-spending non-subscribers.

### 3. 🎟️ Optimize Discount Strategy

Reduce unnecessary discounting on products that already perform well while using targeted promotions for price-sensitive products.

### 4. 🛒 Promote High-Performing Products

Increase visibility of popular and highly rated products through personalized recommendations and campaigns.

### 5. 📦 Optimize Shipping Strategy

Analyze the relationship between shipping options and customer value to improve both customer experience and profitability.

---

## 📂 Project Structure

```text
Customer-Shopping-Analysis/
│
├── 📓 customer_shopping.ipynb
│   └── Python data cleaning, preprocessing & EDA
│
├── 🗄️ sql_analysis.sql
│   └── SQL business analysis queries
│
├── 📊 customer behaviur dashboard.pbix
│   └── Interactive Power BI dashboard
│
├── 📄 Customer Shopping Behavior report.pdf
│   └── Detailed project report
│
├── 📑 Customer-Shopping-Behavior-presentation.pptx
│   └── Project presentation
│
└── 📘 README.md
    └── Project documentation
```

---

## 🚀 How to Explore the Project

### Step 1 — Explore the Python Analysis

Open:

```text
customer_shopping.ipynb
```

Run the notebook to explore the data cleaning, preprocessing, feature engineering, and exploratory analysis.

### Step 2 — Explore the SQL Analysis

Open:

```text
sql_analysis.sql
```

Review the business questions and SQL queries used to analyze customer behavior.

### Step 3 — Open the Power BI Dashboard

Open:

```text
customer behaviur dashboard.pbix
```

Use **Power BI Desktop** to explore the interactive dashboard.

### Step 4 — Read the Full Report

For a detailed explanation of the methodology and findings, see:

```text
Customer Shopping Behavior report.pdf
```

---

## 📊 Skills Demonstrated

This project demonstrates practical skills in:

* 🐍 Python for Data Analytics
* 🐼 Pandas
* 🔢 NumPy
* 🧹 Data Cleaning
* 🔧 Feature Engineering
* 🔍 Exploratory Data Analysis
* 🗄️ SQL
* 📈 Data Visualization
* 📊 Power BI
* 👥 Customer Segmentation
* 💼 Business Intelligence
* 🧠 Business Problem Solving
* 📢 Data Storytelling

---

## 🌟 Why This Project Matters

This project goes beyond simply creating charts.

It demonstrates an **end-to-end analytics workflow**:

> **Raw Data → Clean Data → Business Questions → SQL Analysis → Visualization → Insights → Business Recommendations**

The objective is not just to understand *what happened*, but to identify **why it matters and what a business can do about it**.

---

## 🔮 Future Improvements

Potential extensions to this project include:

* 🤖 Customer purchase prediction using Machine Learning
* 💰 Customer Lifetime Value (**CLV**) prediction
* 🎯 Personalized product recommendation system
* 📈 Sales forecasting
* 🚨 Customer churn prediction
* 🧩 Advanced customer segmentation using clustering
* ⚡ Automated dashboard refresh pipeline

---

## 👨‍💻 Author

**Darksoul0-0**

📊 Data Analytics | Python | SQL | Power BI

If you found this project useful, consider giving the repository a ⭐.

---

## 📜 License

This project is intended for educational and portfolio purposes.
