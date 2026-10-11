# Spotify End-to-End Data Engineering Project using Azure

## Project Overview

This project demonstrates an end-to-end cloud data engineering pipeline built using Microsoft Azure services. The pipeline ingests Spotify music data through an API, stores raw data in Azure Data Lake Storage Gen2, processes and transforms the data, and prepares structured datasets for analytics.

The main objective is to build a scalable data pipeline using Azure Data Factory and other Azure services while applying real-world data engineering concepts such as API integration, ETL/ELT, data lake architecture, data transformation, and pipeline orchestration.

## Architecture

**Pipeline flow:**

Spotify API → Azure Data Factory → Azure Data Lake Storage Gen2 → Data Transformation → Analytics

### Azure Services

* **Azure Data Factory (ADF):** Orchestrates and schedules data ingestion pipelines.
* **Azure Data Lake Storage Gen2 (ADLS Gen2):** Stores raw and processed Spotify data.
* **Azure Databricks (Optional):** Processes and transforms large datasets using PySpark.
* **Azure Synapse Analytics or Azure SQL Database (Optional):** Stores curated data for analytical queries.
* **Power BI (Optional):** Visualizes music trends and analytical insights.
* **Azure Key Vault (Optional):** Securely stores credentials and secrets.

> Note: Optional services will be included only if implemented in the project.

## Project Objectives

* Integrate an external REST API with Azure Data Factory.
* Extract Spotify music metadata using API requests.
* Store raw API responses in Azure Data Lake Storage Gen2.
* Organize data using a raw, proces
