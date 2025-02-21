Azure Data Factory & Databricks Project

Project Overview

This project automates the processing of Excel files stored in Azure Data Lake Storage (ADLS Gen2) using Azure Data Factory (ADF) and Azure Databricks. The pipeline extracts multiple sheets from an Excel file, converts them into Parquet format, and stores the transformed data back into ADLS.

Architecture

Components Used:

Azure Data Factory (ADF): Orchestrates the pipeline workflow.

Azure Data Lake Storage (ADLS Gen2): Stores the source Excel files and processed data.

Azure Databricks: Processes the Excel files using PySpark.

GitHub: Stores all ADF JSON definitions, Databricks notebooks, and configuration files.
