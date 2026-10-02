# Snowflake ETL Demo

## 📌 Overview
This project demonstrates an end-to-end ETL pipeline:
- Raw CSV data ingested into **Snowflake**
- **Stage** and **Pipe** setup for automated loading
- Data transformed into enterprise survey tables
- SQL analysis performed for insights (income vs expenses)

## 🛠 Tech Stack
- Python  
- Snowflake  
- dbt (Data Build Tool)

## 📸 Project Screenshots

### 1. Source Data in S3
![S3 Bucket](docs/screenshot2/S3_bucket.png)

### 2. Stage Creation in Snowflake
![Stage Creation](docs/screenshot2/Stage_creation.png)

### 3. Pipe Setup & Load History
![Pipe Created](docs/screenshot2/pipe_created.png)

### 4. Data Loaded into Enterprise Survey Table
![Enterprise Data](docs/screenshot2/data_enterprise.png)

### 5. SQL Analysis (Income vs Expenses)
![Sum Value](docs/screenshot2/sum_value.png)

## 🚀 Conclusion
This demo highlights how Snowflake integrates with external storage (S3), automates ingestion via pipes, and enables downstream analysis.  
While Cortex AI wasn’t available in the trial, SQL queries provided meaningful insights into enterprise survey data.
