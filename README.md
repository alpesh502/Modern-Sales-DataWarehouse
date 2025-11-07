# Modern Data Warehouse using SQL Server  

Transform raw sales data into **actionable business insights** using a **modern Data Warehouse architecture**! 
This project demonstrates how to design and implement a **complete ETL workflow** with **SQL Server**, applying the **Medallion Architecture (Bronze → Silver → Gold)** framework.  

---

## 🎯 Step 1: Objective  

**Goal:**  
Build a structured **Data Warehouse** that ingests raw data from multiple sources (CRM & ERP systems), cleanses and standardizes it, and produces business-ready analytical data for reporting and insights.

**Key Outcomes:**  
- Automate data ingestion using SQL stored procedures.  
- Implement Medallion Architecture layers for scalability and clarity.  
- Generate analytical insights on customer behavior, product performance, and sales trends.  

---

## 🧠 Step 2: Skills Demonstrated  

✅ SQL Development (DDL, DML, Joins, Subqueries)  
✅ ETL Pipeline Development (Extraction, Transformation, Loading)  
✅ Data Architecture (Bronze, Silver, Gold layers)  
✅ Data Modeling (Fact & Dimension Tables)  
✅ Database Design using **Microsoft SQL Server**  
✅ Data Analytics & Reporting using **SQL Queries / BI Tools**

---

## 🏗️ Step 3: Data Architecture  

The data pipeline follows the **Medallion Architecture** for modular data management:

| Layer | Description |
|-------|--------------|
| 🟫 **Bronze Layer** | Raw data ingestion from CRM and ERP CSV files using `BULK INSERT`. Data is stored “as-is” for traceability. |
| ⚪ **Silver Layer** | Cleans, standardizes, and integrates data from Bronze. Removes duplicates, fixes data inconsistencies, and adds derived columns. |
| 🟨 **Gold Layer** | Final business-ready layer containing analytical tables and joins optimized for BI dashboards and SQL reporting. |

**Architecture Flow:**  

