# SQL Data Warehouse Project

Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

---

## 📖 Project Overview

This project involves:

- **Data Architecture:** Designing a modern data warehouse using the **Medallion Architecture** (Bronze, Silver, Gold layers).  
- **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.  
- **Data Modeling:** Developing optimized **fact** and **dimension** tables for analytical workloads.  
- **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.  

---

## 🎯 Who This Project Is For

This repository is a great resource for anyone looking to demonstrate skills in:

- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🚀 Project Requirements  
### **Building the Data Warehouse (Data Engineering)**

#### **Objective**
Develop a modern data warehouse using **SQL Server** to consolidate sales data and support analytical reporting and informed business decisions.

#### **Specifications**
- **Data Sources:** Import data from two source systems (**ERP** and **CRM**) provided as CSV files.  
- **Data Quality:** Clean and resolve data quality issues before loading data into the warehouse.  
- **Integration:** Combine both data sources into a unified, user-friendly data model for analytics.  
- **Scope:** Focus on the latest available dataset; no historization required.  
- **Documentation:** Provide clear documentation of the data model for business and analytics teams.  

---

## 📁 Project Folder Structure

```text
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
