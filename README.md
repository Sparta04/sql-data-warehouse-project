# SQL Data Warehouse Project

Welcome to my repository! This project demonstrates the end-to-end development of a modern Data Warehouse from scratch using SQL Server. It showcases the complete ETL process, from ingesting raw data to modeling business-ready data for analytics. 

## Project Requirements
* **Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.
* **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality:** Clean and fix data quality issues before analysis.
* **Data Integration:** Combine both of the sources into one single, user-friendly data model that is designed for analytics and reporting.
* **Scope:** Focus on the latest datasets (no historization required).
* **Documentation:** Provide clear documentation of the data model to support business users and analytical teams.

## Data Architecture
This project implements a **Medallion Architecture** to process the data in stages:
* **Bronze Layer (Raw):** Landing zone for raw data extracted directly from the ERP and CRM CSV files.
* **Silver Layer (Cleansed):** Transformed layer where data quality issues are resolved, values are standardized, and missing data is handled.
* **Gold Layer (Business-Ready):** Final layer utilizing a **Star Schema** (Fact and Dimension views) optimized for business intelligence and reporting.

## Licensing
This project is licensed under the MIT License - feel free to use and modify the code.

## About Me
I am a Data Engineering and Software Development student passionate about building scalable data pipelines, enterprise data modeling, and automated ETL workflows. I have experience developing robust backend architectures using tools like SQL Server, Python, PostgreSQL, Docker, and Apache Airflow.
