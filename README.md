# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights practical skills in data engineering, ETL, data modeling, and analytics.

---

## 🏗️ Data Architecture

The data architecture for this project follows **Medallion Architecture**, consisting of **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into SQL Server.

2. **Silver Layer**: This layer includes data cleansing, standardization, validation, and transformation processes to prepare the data for analysis.

3. **Gold Layer**: Houses business-ready data modeled into a star schema for reporting and analytics.

---

## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a modern data warehouse using **Bronze**, **Silver**, and **Gold** layers.

2. **ETL Pipelines**: Extracting, transforming, and loading data from ERP and CRM source systems into the warehouse.

3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.

4. **Analytics & Reporting**: Creating SQL-based reports and analytical queries to generate actionable business insights.

🎯 This project demonstrates practical skills in:

* SQL
* Data Engineering
* ETL Pipeline Development
* Data Warehousing
* Data Modeling
* Data Cleaning & Transformation
* Data Analytics

---

## 🛠️ Tools & Technologies

* **SQL** — Data extraction, transformation, data modeling, ETL, and analytics
* **Git & GitHub** — Version control and project management
* **CSV Files** — Source data from ERP and CRM systems

---

## 🔗 Important Tools

* **SQL** — Used to build the data warehouse, perform ETL processes, transform data, and create analytical queries.

* **Git & GitHub** — Used for version control and managing the project codebase.

* **CSV Files** — Used as the source data files containing ERP and CRM data.

---

## 🚀 Project Requirements

### Building the Data Warehouse — Data Engineering

#### Objective

Develop a modern data warehouse using SQL to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

* **Data Sources**: Import data from two source systems — ERP and CRM — provided as CSV files.

* **Data Quality**: Cleanse and resolve data quality issues before loading data into the analytical layer.

* **Integration**: Combine data from both source systems into a single, user-friendly data model designed for analytical queries.

* **Scope**: Focus on the latest available dataset. Historization of data is not required.

* **Documentation**: Provide clear documentation of the data architecture, data model, and transformations.

---

### BI: Analytics & Reporting — Data Analysis

#### Objective

Develop SQL-based analytics to deliver detailed insights into:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

These insights provide meaningful business metrics to support strategic decision-making.

---

## 📂 Repository Structure

```text
data-warehouse-project/

│
├── datasets/                         # Raw datasets used for the project
│
├── docs/                             # Project documentation and architecture
│   ├── etl.drawio                    # ETL processes
│   ├── data_architecture.drawio      # Project architecture
│   ├── data_catalog.md               # Dataset fields and metadata
│   ├── data_flow.drawio              # Data flow diagram
│   ├── data_models.drawio            # Data models and star schema
│   ├── naming-conventions.md         # Naming conventions
│
├── scripts/                          # SQL scripts for ETL and transformations
│   ├── bronze/                       # Extracting and loading raw data
│   ├── silver/                       # Cleaning and transforming data
│   ├── gold/                         # Creating analytical models
│
├── tests/                            # Data quality and validation tests
│
├── README.md                         # Project overview and documentation
├── LICENSE                           # Project license
├── .gitignore                        # Git ignored files and directories
└── requirements.txt                  # Project requirements
```

---

## 🧪 Data Quality & Testing

Data quality checks are performed throughout the ETL process to ensure that the data is reliable and suitable for analytics.

The project focuses on:

* Checking for duplicate records
* Handling missing and invalid values
* Standardizing data formats
* Validating relationships between tables
* Ensuring consistent data types
* Validating business rules
* Testing the final analytical model

---

## 📊 Analytics

The Gold layer provides business-ready data that can be used to analyze:

### Customer Analytics

* Customer purchasing behavior
* Customer segmentation
* Customer lifetime sales
* Customer demographics
* Top customers

### Product Analytics

* Product performance
* Product sales trends
* Top-performing products
* Product category performance

### Sales Analytics

* Overall sales performance
* Revenue trends
* Monthly and yearly sales
* Order volume
* Average order value
* Customer and product contribution to sales

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share this project with proper attribution.

---

## 👨‍💻 About Me

Hi! I'm **Rohan Raj**, an aspiring **Data Engineer and Data Analytics professional** passionate about working with data and building practical data solutions.

This project is part of my portfolio and demonstrates my hands-on experience with **SQL, data warehousing, ETL pipelines, data modeling, and analytics**.

I'm continuously learning and improving my skills by working on practical projects and exploring modern data technologies.

### Skills Demonstrated

* SQL
* Data Warehousing
* ETL Development
* Data Cleaning
* Data Transformation
* Dimensional Data Modeling
* Star Schema
* Data Analytics
* Git & GitHub

---

⭐ If you find this project useful, feel free to **star the repository** and explore the code!
