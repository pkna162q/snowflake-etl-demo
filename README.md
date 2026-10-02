# Snowflake ETL Demo

## 📌 Overview
This project demonstrates an end-to-end ETL pipeline:
- **Python** loads raw CSV data into **Snowflake**
- **dbt sources** define raw tables
- **dbt staging models** clean and cast data
- **dbt fact models** aggregate metrics (e.g., revenue by industry/year)
- **dbt tests** validate data quality
- **dbt docs** generate lineage graphs and documentation

## 🛠 Tech Stack
- Python  
- Snowflake  
- dbt (Data Build Tool)

## 📸 Project Screenshots

### Lineage Graph
![Lineage Graph](docs/screenshot2/lineage_graph.png)

### Fact Model Details
![Fact Model Details](docs/screenshot2/fact_model_details.png)

### Staging Model Details
![Staging Model Details](docs/screenshot2/staging_model_details.png)

### dbt Run Output
![dbt Run Success](docs/screenshot2/dbt_run_success.png)

### Snowflake Fact Table Preview
![Snowflake Fact Preview](docs/screenshot2/snowflake_fact_preview.png)
