# Retail Sales Data Warehouse using SQL Server

This project showcases the development of a modern SQL Server-based data warehouse for analyzing customer, product, and sales data.

The project implements an end-to-end ETL pipeline using Medallion Architecture (Bronze, Silver, and Gold layers), transforming raw ERP and CRM datasets into a business-ready star schema for analytical reporting.

The objective of this project was to gain hands-on experience with data warehousing concepts including ETL, dimensional modeling, data cleaning, and SQL-based business analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture]()

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## Key Features:

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

Skills Demonstrated

• SQL
• ETL
• Data Modeling
• Data Warehousing
• Data Cleaning
• Analytical SQL
• Star Schema Design

---

##  Important Links & Tools:

- **[Datasets](datasets/):** Access to the project dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.
- **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.
---

## Implementation

• Imported ERP and CRM datasets into SQL Server.

• Built Bronze, Silver and Gold schemas.

• Performed data validation and cleaning.

• Designed dimensional tables.

• Developed analytical SQL queries for reporting.

• Created business-ready datasets for visualization.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---







## 🌟 About Me

I'm Ravi Raj, a B.Tech student at NSUT with interests in SQL, Data Engineering, Analytics, and AI.

This repository documents one of my learning projects focused on modern data warehousing concepts and SQL-based analytics.

## Tech-Stack:

1. SQL Server

2. SSMS

3. Draw.io

4. Git

5. GitHub

6. CSV

7. T-SQL


## What I Learned:

1. Medallion Architecture
2. Star Schema
3. Dimensional Modeling
4. ETL
5. Data Cleaning
6. Data Transformation
7. Fact Tables
8. Dimension Tables
9. SQL Reporting


   ## Future Improvements:
   Future Improvements

  Power BI Dashboard

  Incremental ETL

  Automation using Airflow

  dbt transformations

  Data Quality Monitoring

