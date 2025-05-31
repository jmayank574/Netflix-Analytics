# Netflix-Analytics

This project implements a scalable ELT pipeline for processing Netflix streaming data using Azure Data Factory, Databricks, and Delta Live Tables, structured with the Medallion architecture. It enables incremental ingestion, schema validation, and governance for downstream analytics.

# Concepts Implemented

ELT architecture using Azure and Databricks

Medallion design pattern (Bronze, Silver, Gold layers)

Delta Live Tables (DLT) for transformation and data quality

Schema enforcement and change tracking

Unity Catalog for governance and access control

# Key Features

Data Ingestion: Parameterized ADF pipeline to ingest data from GitHub to ADLS Gen2 (Bronze)

Data Transformation: Incremental cleaning and enrichment in Databricks using Auto Loader and PySpark (Silver)

Data Warehousing: Gold layer with DLT for schema validation and trusted analytics output

Governance: Unity Catalog for secure and centralized metadata management

# Technologies Used

Azure Data Factory

Azure Data Lake Storage Gen2

Azure Databricks (PySpark + Auto Loader + DLT)

Delta Lake

Unity Catalog

# Project Architecture

![image](https://github.com/user-attachments/assets/6a72a35e-4bf0-4799-b161-019074a5c6f7)
