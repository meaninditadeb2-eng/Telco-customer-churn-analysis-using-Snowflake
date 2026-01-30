# Telco-customer-churn-analysis
# Telco Customer Churn Analytics Platform
End-to-End Snowflake & Power BI Analytics Project

---
## 🚀 Getting Started

This project requires Snowflake and Power BI.

### ❗ Prerequisites
- Snowflake account
- Power BI Desktop
- Telco customer churn dataset in `/DATA`

### 📁 Setup Instructions
1. Load the dataset into Snowflake stage.
2. Run SQL scripts from `SQL/01_database_schema.sql` → through `SQL/BI_layer_views.sql`
3. Open the Power BI file in `/DASHBOARD/Telco_Churn_Dashboard.pbix`
4. Connect Power BI to Snowflake using your Snowflake credentials


## 📖 Project Overview
This project implements an enterprise-style analytics platform to analyze customer churn behavior for a telecom company.  
It follows a **layered data architecture** in Snowflake to ensure scalability, data quality, governance, and BI readiness.

The final insights are delivered through a professional **Power BI dashboard**.

---

## 🛠 Tech Stack
- **Snowflake** – Cloud Data Warehouse
- **SQL** – Data Transformation & Analytics
- **Power BI** – Business Intelligence & Visualization
- **CSV Dataset** – Telco Customer Churn Data

---

## 🏗 Architecture Overview
RAW
↓
CLEAN
↓
DATA_QUALITY
↓
SEMANTIC
↓
ANALYTICS
↓
BI_LAYER
↓
Power BI Dashboard


Additional cross-cutting layers:
- SECURITY_GOVERNANCE
- COST_MONITORING

---

## 🧱 Data Layers Explained

### 1️⃣ RAW Layer
- Stores raw ingested data from source files
- No transformations applied
- Preserves source fidelity

**Purpose:** Auditing, traceability, and reprocessing

---

### 2️⃣ CLEAN Layer
- Data type standardization
- Null handling
- Column normalization
- Business-ready cleaned tables

**Purpose:** Reliable, structured data foundation

---

### 3️⃣ DATA_QUALITY Layer
- Validation checks (row counts, null checks, domain checks)
- Data completeness and consistency verification
- Error detection for upstream data issues

**Purpose:** Trustworthy analytics and reporting

---

### 4️⃣ SEMANTIC Layer
- Business-friendly definitions
- Derived fields and standardized metrics
- Consistent naming conventions

**Purpose:** Single source of truth for metrics

---

### 5️⃣ ANALYTICS Layer
- KPI and aggregation tables
- Churn analysis by:
  - Contract Type
  - Internet Service
  - Tenure Groups
- Revenue impact analysis
- High-risk customer segmentation

**Purpose:** Business insight generation

---

### 6️⃣ BI_LAYER
- Power BI optimized tables/views
- Pre-aggregated metrics
- Minimal transformation in BI tool

**Purpose:** Performance and simplicity in dashboards

---

### 7️⃣ SECURITY_GOVERNANCE
- Role-based access control
- Schema-level and object-level permissions
- Separation of duties

**Purpose:** Data protection and compliance

---

### 8️⃣ COST_MONITORING
- Warehouse usage tracking
- Query performance monitoring
- Cost visibility and optimization

**Purpose:** Cost-efficient data operations

---

## 📊 Power BI Dashboard
The Power BI dashboard provides:
- Overall churn rate
- Total vs churned customers
- Churn by contract and tenure
- Average monthly charges
- Customer-level drill-down

Designed as a **single-page executive dashboard** for fast decision-making.

---

## 🔍 Key Business Insights
- Month-to-month contracts have the highest churn rate
- Customers with tenure under one year are high risk
- Long-term contracts significantly reduce churn
- Higher monthly charges correlate with churn probability

---

## 🚀 Learning Outcomes
- Enterprise data modeling in Snowflake
- Layered analytics architecture
- SQL-based KPI engineering
- BI-first data design
- Cost and governance awareness

---

## 📬 Author
**Anindita Deb**  
Aspiring Data Scientist | Analytics Engineer Enthusiast





