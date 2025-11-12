# Modern Data Warehouse using SQL Server  

Transform raw sales data into **actionable business insights** using a **modern Data Warehouse architecture**! 
This project demonstrates how to design and implement a **complete ETL workflow** with **SQL Server**, applying the **Medallion Architecture (Bronze → Silver → Gold)** framework.  

---

##  Step 1: Objective  

**Goal:**  
Build a structured **Data Warehouse** that ingests raw data from multiple sources (CRM & ERP systems), cleanses and standardizes it, and produces business-ready analytical data for reporting and insights.

**Key Outcomes:**
- Automate data ingestion using SQL stored procedures.
- Implement Medallion Architecture layers for scalability and clarity.
- Generate analytical insights on customer behavior, product performance, and sales trends.

---

##  Step 2: Skills Demonstrated  

 - SQL Development (DDL, DML, Joins, Subqueries)
 - ETL Pipeline Development (Extraction, Transformation, Loading)
 - Data Architecture (Bronze, Silver, Gold layers)
 - Data Modeling (Fact & Dimension Tables)
 - Database Design using **Microsoft SQL Server**

---

##  Step 3: Data Architecture  

The data pipeline follows the **Medallion Architecture** for modular data management:

| Layer | Description |
|-------|--------------|
|  **Bronze Layer** | Raw data ingestion from CRM and ERP CSV files using `BULK INSERT`. Data is stored “as-is” for traceability. |
|  **Silver Layer** | Cleans, standardizes, and integrates data from Bronze. Removes duplicates, fixes data inconsistencies, and adds derived columns. |
|  **Gold Layer** | Final business-ready layer containing analytical tables and joins optimized for BI dashboards and SQL reporting. |


##  Step 4: Data Architecture Design

A robust data-warehouse architecture was designed to support scalable ETL operations and organized data flow.
It defines how data travels through ingestion, transformation, and reporting layers, ensuring reliability and modularity.

![Data Architecture](https://github.com/alpesh502/Modern-Sales-DataWarehouse/blob/main/docs/data_architecture.png)

---
##  Step 5: Data Flow

The data-flow diagram explains the movement of data across systems — from source files (CSV) to data warehouse tables and finally to BI dashboards.
It helps visualize dependencies, data refresh frequency, and transformation logic.

![Data Flow](https://github.com/alpesh502/Modern-Sales-DataWarehouse/blob/main/docs/data_flow.png)

---
##  Step 6: Data Integration

Data from CRM and ERP systems is integrated using SQL Server stored procedures and BULK INSERT for batch ingestion.
This step ensures data consistency, proper mapping, and incremental loading for updates.

![Data Integration](https://github.com/alpesh502/Modern-Sales-DataWarehouse/blob/main/docs/data_integration.png)

---
## Step 7: Data Modeling

Data Modeling is performed using Fact and Dimension tables for better analytics and reporting.
This model supports star schema design, enabling faster queries and simplified dashboard development.

![Data Model](https://github.com/alpesh502/Modern-Sales-DataWarehouse/blob/main/docs/data_model.png)

--- 
##  Step 8: Conclusion

This project demonstrates an end-to-end Data Warehouse and Analytics solution built on SQL Server and Azure services.
By following the Medallion Architecture (Bronze → Silver → Gold), the pipeline ensures:
- Clear data lineage and traceability
- High-quality, consistent data for decision-making
- Scalable architecture ready for real-time analytics

Result: Raw data transformed into insightful business intelligence — powering data-driven decisions efficiently.
