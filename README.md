# Fabric_Sales_Report
**Project Overview**
The Fabric Sales Report is an end-to-end sales analytics solution built using Microsoft Fabric and Power BI.
The project demonstrates an automated data workflow where sales data is ingested using a Microsoft Fabric Data Pipeline, processed using the Medallion Architecture, stored in a Fabric Lakehouse, and connected to Power BI for interactive reporting and analysis.
<img width="946" height="506" alt="Screenshot 2026-10-02 020617" src="https://github.com/user-attachments/assets/85c7c32e-e819-40ad-b92f-6e9923e91dd9" />
**Business Objective**
The objective of this project is to help business teams:
Monitor overall sales performance
Track revenue and Quantity Sold
Analyze sales by product and category
Compare regional sales performance
Identify top-performing products
Identify top customers by revenue
Support data-driven business decisions
**Tools & Technologies**
Microsoft Fabric
Fabric Data Pipeline
Fabric Lakehouse
OneLake
Medallion Architecture
Bronze Layer
Silver Layer
Gold Layer
Data Transformation
SQL Analytics Endpoint
Notebook/PySpark 
**Data Pipeline & Automation**
A Microsoft Fabric Data Pipeline is used to automate the ingestion of sales data from GitHub into the Fabric environment.
The automated workflow includes:
Sales data is maintained in GitHub
Fabric Data Pipeline retrieves the dataset
Raw data is loaded into the Bronze Layer
Data is cleaned and transformed in the Silver Layer
Business-ready data is prepared in the Gold Layer
The Gold Layer is connected to Power BI
Power BI is used to create the interactive sales dashboard

**Medallion Architecture**
The project follows the Medallion Architecture to organize data into three progressive layers.
**Bronze Layer — Raw Data**
The Bronze Layer stores the original data ingested from GitHub.
Activities include:
Ingesting the source CSV dataset
Preserving the original data
Storing raw sales information in the Fabric Lakehouse

**Silver Layer — Cleaned & Transformed Data**
The Silver Layer contains cleaned and transformed data.
Activities include:
Data cleaning
Handling data quality issues
Datatype conversion
Removing unnecessary data
Standardizing fields
Preparing data for analysis

**Gold Layer — Business-Ready Data**
The Gold Layer contains the final data prepared for reporting and business analysis.
Activities include:
Creating business-ready datasets
Preparing analytical fields
Creating aggregations where required
Validating data for reporting
Connecting the prepared data to Power BI

**Key Business Questions**
The dashboard helps answer:
Which products categories the highest revenue?
Which product categories have the best quantity sold?
Which regions contribute the most to sales?
Which customer segments generate higher revenue?
Which products are the top performers by region?
