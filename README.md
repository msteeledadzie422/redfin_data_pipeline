# Redfin City Real Estate Data Pipeline

This is an ETL data engineering project that uses Apache Airflow, Snowpipe, Snowflake, and AWS Services to extract real estate data from Redfin.
Using Airflow hosted on an AWS EC2 Instance, raw Redfin data is pulled into an AWS S3 bucket, transformed and loaded into another AWS S3 bucket before ultimately being loaded into a Snowflake data warehouse via Snowpipe.

Project composed with aid from tutorial ["Redfin Analytics|python ETL pipeline with airflow|Data Engineering Project|Snowpipe|Snowflake"](https://www.youtube.com/watch?v=NWZrBEnJ6Us) by Yemi Olani.

### Airflow DAG Graph

![airflow_dags](assets/redfin_airflow_dags.png)

### AWS S3 Buckets

![aws_s3_bucket_1](assets/redfin_s3_bucket_raw.png)

![aws_s3_bucket_2](assets/redfin_s3_bucket_transformed.png)

### Snowflake Data Warehouse Creation

![snowflake](assets/redfin_snowflake.png)

