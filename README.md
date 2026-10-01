# Customer-Churn-Analysis
Customer Churn Analysis project using SQL, SQLite, Python, Pandas, NumPy, Matplotlib and Seaborn. Analyzes customer, subscription and support data to identify churn patterns, customer segments, revenue impact and support-related churn signals, translating data into actionable business insights.
# Customer Churn & Retention Analysis

## 📌 Project Overview

This project analyzes a dummy OTT subscription dataset to understand customer churn, identify high-churn customer segments, and evaluate the business impact of customer loss.

The project integrates customer, subscription, and support data and follows an end-to-end data analysis workflow:

**SQL/SQLite → Data Cleaning → Feature Engineering → EDA → KPI Analysis → Visualization → Business Insights**

---

## 🎯 Business Problem

The objective of this project is to answer:

- How many customers are churning?
- Which customer segments have higher observed churn?
- How does churn vary across subscription plans, states and acquisition channels?
- What is the revenue impact of customer churn?
- Is there a relationship between support escalations and churn?
- What areas should the business investigate for customer retention?

---

## 🛠️ Tools & Technologies

- **SQL**
- **SQLite**
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## 🔍 Project Workflow

### 1. Data Extraction
Connected Python to a SQLite database and extracted data from multiple relational tables.

### 2. Data Cleaning
- Handled missing values
- Converted date columns
- Standardized categorical values
- Removed unnecessary columns
- Performed data quality checks

### 3. Feature Engineering
Created analytical features such as:
- Customer tenure
- Churn flag
- Complaint count
- Churn risk categories
- Revenue-related metrics

### 4. Data Analysis
Performed analysis using:
- SQL queries
- GroupBy and aggregations
- Segmentation
- KPI calculations
- Correlation analysis

### 5. Visualization
Created visualizations using Matplotlib and Seaborn to understand:
- Churn by subscription plan
- Churn by state
- Churn by acquisition channel
- Revenue impact
- Support escalation and churn relationship

---

## 📊 Key Findings

- Overall observed churn rate: **28.57%**
- Referral segment showed **83.33% observed churn**
- Basic plan showed **60% observed churn**
- Support escalation status showed a **0.77 positive correlation with churn**
- Churn and revenue impact were further analyzed using customer tenure, monthly charges and CLTV.

> Note: The dataset is a dummy/practice dataset, so these findings represent observations within this dataset and should not be generalized to a real customer population.

---

## 💡 Business Takeaway

The analysis highlights customer segments and support-related patterns that may require further investigation for retention efforts. The project demonstrates how SQL and Python can be used to transform relational customer data into measurable business insights.

---

## 👨‍💻 Skills Demonstrated

**SQL | Python | Data Cleaning | Feature Engineering | Exploratory Data Analysis | KPI Analysis | Data Visualization | Business Analysis | Problem Solving**
