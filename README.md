# ecommerce-data-engineering-pipeline
# SoftCart Ecommerce Data Platform

This project demonstrates a hybrid ecommerce data platform using MySQL, MongoDB, PostgreSQL, Hadoop, Spark, Airflow, and BI dashboards.

The system simulates an ecommerce company where product catalog data is stored in MongoDB, transactional sales and inventory data are stored in MySQL, and periodic ETL pipelines move operational data into a PostgreSQL staging warehouse. Hadoop and Spark are used for large-scale analytics, while BI tools are used to build operational dashboards.

## Architecture

- MySQL: stores transactional sales and inventory data
- MongoDB: stores product catalog data
- PostgreSQL: staging data warehouse
- Hadoop: big data storage platform
- Spark: distributed analytics engine
- Apache Airflow: ETL orchestration
- IBM Cognos Analytics / Google Looker Studio: BI dashboard layer

## Data Flow

1. Customers interact with the ecommerce website.
2. Product catalog data is served from MongoDB.
3. Sales and inventory transactions are stored in MySQL.
4. Airflow runs scheduled ETL pipelines.
5. Data is extracted from MySQL and loaded into PostgreSQL.
6. Analytical data is collected into Hadoop.
7. Spark processes data on Hadoop for business insights.
8. BI dashboards visualize sales, inventory, and operational metrics.

## Disclaimer

This project is inspired by a learning scenario from a data engineering capstone course. The implementation, code, sample data, and documentation in this repository are independently created for portfolio purposes.
