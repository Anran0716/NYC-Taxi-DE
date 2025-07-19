# NYC-Taxi-DE

This project builds an end-to-end data engineering pipeline using NYC Taxi Trip dataset. It showcases how to collect, process, store, and analyze large-scale taxi data with ETL pipelines.

**Key Highlights:**
- **Data Ingestion:** Automated extraction of raw taxi trip data from public sources with Python.

- **Data Processing:** Cleaned and transformed millions of trip records with Python (Spark) and SQL (Google BigQuery).

- **Data Orchestration:** Workflow automation with Airflow & Docker.

- **Data Storage:** Structured storage in PostgreSQL and Google Cloud Platform.

- **Analytics & Visualization:** Performed exploratory analysis and built dashboards to show trip trends, popular routes, and revenue insights.

## Datasets

* Yellow taxi data: https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/yellow
* Green taxi data: https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/green
* For-hire vehicles (FHV): https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/fhv
* For-hire vehicles high volume (FHVHV): https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/fhvhv
* Misc (zone lookup file): https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/misc

The data was copied from the [NYC TLC website](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)


### Tools & Technology
- **Cloud Provider:** Google Cloud Platform (GCP)
- **Infrastructure as Code:** Terraform
- **Orchestration:** Mage (Containerized with Docker)
- **Data Processing:** DBT for transformations
- **Storage & Querying:** GCS, BigQuery, Spark
- **Visualization:** PowerBI, Looker Studio 

### Dashboard & Visualization

Coming soon ... 

## General Guidance

- [**Workflow Orchestration - ETL**](https://github.com/Anran0716/NYC-Taxi-DE/tree/main/Workflow%20Orchestration%20-%20ETL)

- [**Analytics Engineering - DBT**](https://github.com/Anran0716/NYC-Taxi-DE/tree/main/Analytics%20Engineering%20-%20DBT)

- [**Batch Processing - Spark**](https://github.com/Anran0716/NYC-Taxi-DE/tree/main/Batch%20Processing%20-%20Spark)