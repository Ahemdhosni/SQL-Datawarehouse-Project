# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository. This project presents an end-to-end data warehousing and analytics solution, covering data ingestion, transformation, modeling, and reporting. It is designed as a portfolio project to demonstrate practical data engineering and analytics skills using industry-standard approaches.

## Overview

This project focuses on building a modern data warehouse in SQL Server and transforming raw data into analytics-ready models for reporting and business insight generation.

The solution includes:

- Designing a layered data architecture
- Building ETL pipelines from source files into SQL Server
- Cleaning and standardizing source data
- Modeling business data using fact and dimension tables
- Producing SQL-based analytics for reporting and decision-making

## Data Architecture

The project follows the **Medallion Architecture** approach with three logical layers:

<img width="1544" height="912" alt="image" src="https://github.com/user-attachments/assets/a9fe03dd-c826-4de9-abf6-b72f5f4d1fc9" />


### Bronze Layer
Stores raw data ingested directly from source systems into SQL Server without modification.

### Silver Layer
Applies cleansing, standardization, validation, and transformation to improve data quality and prepare the data for downstream use.

### Gold Layer
Delivers business-ready data modeled as a star schema to support reporting, analytics, and performance-focused SQL queries.

## Project Goals

### Data Engineering
Build a centralized data warehouse that consolidates sales-related data from multiple source systems and prepares it for analysis.

### Analytics and Reporting
Generate SQL-based insights that help stakeholders understand:

- Customer behavior
