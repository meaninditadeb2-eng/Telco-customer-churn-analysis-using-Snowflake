# Telco-customer-churn-analysis
# Telco Customer Churn Analysis | Snowflake & Power BI

## 📌 Project Overview
This project focuses on analyzing customer churn behavior for a telecom company using a modern data analytics stack.  
The goal is to identify churn drivers, calculate key churn KPIs, and present insights through a professional Power BI dashboard.

---

## 🛠 Tech Stack
- **Snowflake** – Data Warehousing
- **SQL** – Data transformation & analytics
- **Power BI** – Data visualization & dashboarding
- **CSV Dataset** – Telco Customer Churn data

---

## 🏗 Architecture
RAW Layer → CLEAN Layer → ANALYTICS Layer → Power BI Dashboard


---

## 🧱 Data Layers

### 1. RAW Layer
- Loaded raw CSV data using Snowflake stage and file format
- No transformations applied

### 2. CLEAN Layer
- Data cleaning and standardization
- Handled nulls and data types
- Prepared analysis-ready tables

### 3. ANALYTICS Layer
Created KPI tables and views:
- Overall Churn Rate
- Churn by Contract Type
- Churn by Internet Service
- Churn by Tenure Group
- Revenue Impact of Churn
- High-Risk Customer Segments

---

## 📊 Power BI Dashboard
Key insights displayed:
- Overall churn percentage
- Total vs churned customers
- Churn distribution by contract and tenure
- Average monthly charges
- Customer-level drill-down

The dashboard is designed as a **single-page executive view** for quick decision-making.

---

## 🔍 Key Insights
- Month-to-month customers show the highest churn
- Customers with tenure less than 1 year are at high risk
- Higher monthly charges correlate with higher churn probability
- Long-term contracts significantly reduce churn

---

## 🚀 Outcome
This project demonstrates an end-to-end analytics workflow:
✔ Data warehousing  
✔ SQL analytics  
✔ Business KPI modeling  
✔ Professional dashboard design  

---

## 📬 Author
**Anindita Deb**  
Aspiring Data Scientist | Analytics Enthusiast  
