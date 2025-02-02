# Azure Data Engineering Project - NYC Taxi Data Pipeline

## Overview
This project builds an automated data pipeline for the NYC Taxi dataset using Microsoft Azure services. It ingests, transforms, and serves taxi trip data efficiently.

NYC Taxi Data: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Workflow
1. **Azure Setup**: Resource Group, Data Lake Storage Gen2, Data Factory, Databricks.
2. **Data Ingestion**: NYC Taxi data collected via API, stored in Data Lake.
3. **Transformation**: Databricks cleans and processes data into Parquet format.
4. **Serving & Warehousing**: Data stored in Delta Lake, queried via Synapse Analytics.
5. **Security**: Azure Active Directory and Key Vault for access control.
6. **Reporting**: Power BI dashboards for insights.

## Tech Stack
Azure Data Factory, Databricks, Delta Lake, Power BI, AAD, Key Vault.

## Outcome
- Automated data ingestion and processing.
- Efficient storage with Parquet and Delta Lake.
- Interactive Power BI dashboards.

A scalable and secure Azure-based data engineering solution for NYC Taxi data.
