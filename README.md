# Dynamic_Data_Orchestration_Using_ADF_and_DevOps-
**Overview**:

A dynamic pipeline using Azure Data Factory, ingesting data from on-premises file storage, SQL databases, and GitHub into Azure Data Lake; along with incremental loading without watermark tables and transformations using Parquet, JSON,  and Delta formats.We follow a medallion architecture with automated orchestration and monitoring through Azure Logic Apps,and setup full
 CI/CD using Azure Dev Ops.

**Project Flowchart**

<img width="350" height="350" alt="Architecture FlowChart" src="https://github.com/user-attachments/assets/1d5dda22-081d-44a5-a8cc-fce653204752" />


**Architecture Overview**

1. Data Ingestion: Data is being ingested from On Prem Files, Azure SQL DB and GitHub using ADF Pipelines to the Bronze Layer (To get in-depth understanding of the steps followed and flow of Pipelines refer to : **"Documentation - Pipeline Creation"** file and **Template Files uploaded for the respective pipelines**)
2. Data Processing: Using ADF, we perform transaformations on this data and provide data for our Silver and Gold Layer. (**Refer to "Project Documentation - Data Flow Transformations" file for Silver Load process**)
3. Miscellaneous: Using Logic Apps, we have developed alerts for pipeline failures, and used Azure Devops to implement CI/CD for our pieplines

**Author**
 Pranav Arora - www.linkedin.com/in/pranav-arora4

 
