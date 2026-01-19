

<img width="1373" height="582" alt="Screenshot 2026-01-19 205758" src="https://github.com/user-attachments/assets/78725d48-4095-47c9-b2ea-b690084c1efd" />




<img width="1333" height="579" alt="Screenshot 2026-01-14 164832" src="https://github.com/user-attachments/assets/5d598dbe-600b-4311-821e-666f0f1ea450" />



<img width="1288" height="545" alt="Screenshot 2026-01-14 164944" src="https://github.com/user-attachments/assets/1308761b-f310-4ee3-8ecc-7da9d5a2ef7b" />




Azure End-to-End Data Engineering Project

📌 Project Overview
This project demonstrates a robust data engineering pipeline built on Microsoft Azure. The goal is to ingest, transform, and analyze data using modern cloud-based tools, moving data from raw sources to a structured format for business intelligence and reporting.

🏗️ Architecture
The pipeline follows a standard "Medallion Architecture" (Bronze, Silver, and Gold layers):

Ingestion: Data is pulled from source systems using Azure Data Factory.

Storage: Raw and processed data is stored in Azure Data Lake Storage (ADLS) Gen2.

Transformation: Data cleaning and aggregation are performed using Azure Databricks (PySpark).

🛠️ Technologies Used
Azure Data Factory (ADF): For orchestration and ETL pipelines.

Azure Databricks: For scalable data processing and Spark-based transformations.

Azure Data Lake Storage Gen2: As the central repository for big data.

Azure SQL Database / Synapse: For data warehousing.

Azure Key Vault: For managing secrets and connection strings.

PySpark/SQL: For data manipulation.

🚀 Key Features
Automated Ingestion: Daily triggers to fetch new data from APIs or on-premise sources.

Data Lake Organization: Structured folders for Raw, Cleansed, and Curated data.

Scalability: Built to handle large datasets using Databricks clusters.

Security: Implemented secret-scope integration between Key Vault and Databricks.
