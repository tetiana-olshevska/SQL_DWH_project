# SQL Data Warehouse Project
This project is aimed at building and designing Data Warehouse using SQL Server that follows a layered Medallion Architecture. It demonstrates the full ETL pipeline process, from ingesting raw ERP and CRM data to transforming it into a structured, analytical format (star schema) that supports reporting, business intelligence, and data-driven decision-making.

---
## 🏗️ Data Architecture

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

<img width="963" alt="image" src="https://github.com/user-attachments/assets/2a090af8-2432-4e6d-92fb-02cf926f9c6d" />

---
## 🔧 Project Components

- ETL Pipelines: SQL scripts that extract, transform, and load data across the three layers.
- Data Modeling: Design of fact and dimension tables to support analytical queries.
- Analytics & Reporting: SQL-based reports providing insights into customer behavior, product performance, and sales trends.

---
Credits: https://www.datawithbaraa.com/sql-introduction/advanced-sql-project/
