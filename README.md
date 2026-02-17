# 🏗 SQL Data Warehouse & Analytics Project

## 📌 Project Overview

This project demonstrates the design and implementation of a modern SQL-based Data Warehouse using Medallion Architecture (Bronze, Silver, Gold).

Raw datasets are transformed into structured, analytics-ready star schemas to support scalable reporting and business intelligence.

---

# 🏗 Data Architecture

![Data Warehouse Flow](docs/DWH%20flow_white_bg.png)

The warehouse follows a **Medallion Architecture**:

### 🥉 Bronze Layer
- Raw data ingestion from source files
- Stored as-is for traceability and auditing

### 🥈 Silver Layer
- Data cleansing & transformation
- Standardization and normalization
- Business logic application

### 🥇 Gold Layer
- Star schema modeling
- Fact & dimension tables
- Optimized for analytical queries

---

# 🔄 Dataset Flow

![Dataset Flow](docs/Dataset%20flow_white_bg.png)

- Source data → Staging → Transformation → Analytics-ready tables
- Structured ETL pipeline for scalable processing

---

# 🗂 Integration Model

![Integration Model](docs/integration%20model_white_bg.png)

- Consolidated datasets across domains
- Defined relational joins and key mappings
- Ensured referential integrity

---

# ⭐ Star Schema (Data Mart)

![Star Schema](docs/star%20schema%20dt%20mart_white_bg.png)

- Central fact table for measurable events
- Connected dimension tables (Date, Customer, Product, etc.)
- Designed for efficient aggregations and reporting

---

# ⚙️ Technical Implementation

- SQL Server Data Warehouse Design
- Layered ETL Pipelines
- Fact & Dimension Modeling
- Primary & Foreign Key Constraints
- Query Optimization Techniques
- Analytical SQL Reporting

---

# 🛠 Skills Demonstrated

- Data Warehousing Concepts
- Medallion Architecture (Bronze/Silver/Gold)
- ETL Design & Transformation Logic
- Star Schema Modeling
- SQL Aggregations & Window Functions
- Data Normalization
- Performance Optimization

---

# 💼 Why This Project Matters

This project demonstrates:

- Strong understanding of modern data architecture
- Ability to design scalable analytical systems
- Structured ETL pipeline development
- Business-focused data modeling
- Advanced SQL analytics capability

These skills directly align with Data Analyst, BI Analyst, and Analytics Engineer roles.



---

