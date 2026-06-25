# Data Warehouse Project

Welcome to my **Data Warehouse Project**! 🚀  
I built this data warehouse and analytics pipeline completely from scratch. It covers the entire data lifecycle, from taking raw, messy source data and engineering ETL pipelines to designing the star schemas needed to answer real business questions and power actual reports.

![Data Warehouse — Medallion Architecture](./docs/architecture_animated.svg)

---
## 🏗️ Data Architecture

The data architecture for this project follows the Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server Database.
2. **Silver Layer**: This layer handles data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema optimized for reporting and analytics.

---
## 📖 Project Overview

### 📋 Project Management & Agile Workflow

To ensure a structured development process, the entire lifecycle of this project—from initial architecture design to final analytical queries—was tracked step-by-step using **Notion**. 

You can view my complete task board, sprint breakdown, and workflow documentation here: **[View my Notion Project Board](https://www.notion.so/SQL-Data-Warehouse-Project-dd01d447fae5835da87c814af18a16b0?source=copy_link)**

This project showcases the following core technical skills:

1. **Data Architecture**: Designing a Modern Data Warehouse using the Medallion Architecture.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable business insights.

### Tools & Technologies Used:
- **Database:** SQL Server Express / SQL Server Management Studio (SSMS)
- **Languages:** T-SQL
- **Version Control:** Git & GitHub
- **Architecture Design:** DrawIO

---
## 🚀 Project Requirements & Execution

### Phase 1: Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Imported data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleansed and resolved data quality issues (e.g., handling nulls, standardizing formats) prior to analysis.
- **Integration**: Combined both sources into a single, user-friendly data model designed for analytical queries.
- **Documentation**: Provided clear documentation of the data model to support both business stakeholders and analytics teams.

---

### 📈 Phase 2: Data Analytics & Business Intelligence

#### Objective
Developed SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

This repository covers the backend Data Engineering (extracting, cleansing, and modeling the data into a Star Schema). 

To see how I utilized the resulting **Gold Layer** to extract strategic business insights, perform customer segmentation, and track KPIs using advanced T-SQL, check out the second half of this project:

> **View the Business Intelligence phase here:** > [SQL Data Analytics & Reporting Project](https://github.com/KrishnaSai315/SQL-Data-Analytics/tree/main)

These insights help stakeholders understand key business metrics and make strategic decisions.  

---

## 📂 Repository Structure
```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture diagrams
│   ├── data_architecture.png           # High-level overall Data Architecture diagram
│   ├── bronze_layer.png                # Visual of the Bronze Layer (Raw Data ingestion)
│   ├── silver_layer.png                # Visual of the Silver Layer (Cleansed/Standardized Data)
│   ├── gold_layer.png                  # Visual of the Gold Layer (Business-Ready Data)
│   ├── integration_model.png           # Business logic showing CRM and ERP data integration
│   ├── star_schema.png                 # Gold layer data model (Fact and Dimension tables)
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   └── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   └── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality checks
│
├── README.md                           # Project overview and instructions
└── .gitignore                          # Files and directories ignored by Git
```
---
## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.


### Why I Built This Project

I developed this repository to demonstrate my ability to own the entire data lifecycle from end to end. I wanted to demonstrate that I can bridge the gap between building resilient backend data architecture and delivering front-end business value, proving I can handle both the heavy lifting of data engineering and the nuanced logic of advanced analytics.

### What I Accomplished Here

Architected a Data Warehouse: Designed and built a modern data warehouse from scratch using the industry-standard Medallion Architecture.

Engineered ETL Pipelines: Wrote robust T-SQL scripts to extract raw, fragmented ERP and CRM data (Bronze), cleanse and normalize it (Silver), and model it into a high-performance Star Schema (Gold).

Delivered Business Intelligence: Transformed chaotic CSV files into a centralized, single source of truth capable of answering complex business questions regarding customer segmentation, product inventory, and sales forecasting.



## 🙌 Acknowledgements

**Data with Baraa:** Special thanks😊 for providing the foundational dataset and project concept that inspired this end-to-end analytics build.
