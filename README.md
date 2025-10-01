# Azure Data Warehouse & ETL Pipeline Project

This project demonstrates the design and implementation of a cloud-based data warehouse and ETL pipeline, integrating multiple sources into a dimensional model for retail analytics.

## Project Overview
- Designed a star schema data warehouse with fact and dimension tables.  
- Implemented ETL pipelines using:
  - Azure Data Factory – to orchestrate data ingestion from:
    - Azure SQL Database
    - JSON files in Azure Blob Storage
  - SSIS (SQL Server Integration Services) – replicated workflows locally with Excel as a source, transformations (derived columns, conditional splits, aggregates), and outputs to flat files.  
- Created a Date Dimension via SQL scripting.  
- Validated outputs with analytical SQL queries.  

##  Technologies Used
- Azure SQL Database  
- Azure Data Factory (ADF)  
- Azure Blob Storage  
- SSIS (SQL Server Integration Services)  
- SQL Server  

## Project Report
The detailed project documentation, including schema diagrams, ETL workflows, and query examples. 

---

## Key Highlights
- End-to-end ETL process from heterogeneous sources to cloud data warehouse.  
- Dimensional modeling (fact + dimension tables) for analytical queries.  
- Automated data flows and transformations using ADF + SSIS.  

---

## How to Use
1. Review the **[Azure Datawarehouse Pipeline.pdf]** for schema diagrams, ETL workflows, and query samples.  
2. Explore the **ETL steps** to understand ingestion, transformation, and loading into the warehouse.  
3. Adapt the SQL scripts and workflows for your own Azure or SSIS setup.  


