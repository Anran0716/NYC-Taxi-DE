# Batch Processing - Spark
In the this section, we'll use SQL in Spark to process the NTC Taxi data.

## 1. Preparing Taxi Data
### a. Downloading the data
Use this bash script to download Yellow and Green Taxi Data: [`download_data`](Code/download_data.sh). This script automates the process of downloading NYC taxi trip data for a given taxi type and year, saving each month’s data in an organized folder structure.

### b. Reading CSVs and converting to parquet
This script uses PySpark to process and transform raw CSV files containing green taxi trip data into Parquet format.
- Green taxi code: [`green_taxi_data.py`](Code/green_taxi_data.py)
- Yellow taxi code: [`yellow_taxi_data.py`](Code/yellow_taxi_data.py)

## 2. SQL with Spark
- Load the data
- Find common columns
- Combine yellow and green data
- Query with SQL

Code: 
- [`pyspark_sql.py`](Code/pyspark_sql.py)
- [`pyspark_sql2.py`](Code/pyspark_sql2.py)

## 3. Run Spark in the Cloud

1. Upload the files to GCS
2. Download the Cloud Storage Connector for Hadoop
3. Configure Spark and Hadoop to Use the Cloud Storage Connector

Code:
- [`spark_bucket.py`](Code/spark_bucket.py)
- [`spark_dataframes.py`](Code/spark_dataframes.py)

## 4. Connect Spark to Big Query
- [`pyspark_sql_bigquery.py`](Code/pyspark_sql_bigquery.py)
