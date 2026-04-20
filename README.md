# Databricks Streaming Data Pipeline

## Project Overview

This project implements a real-time data pipeline using Databricks, Spark Structured Streaming, and Delta Lake following the Medallion Architecture (Bronze, Silver, Gold).

##  Architecture

Streaming ingestion (simulated real-time data)
Bronze layer (raw data)
Silver layer (cleaned & validated data)
Gold layer (business KPIs)

## Key Features
Real-time data processing
Data quality checks
Deduplication
Partitioned Delta tables
Business metrics (revenue, active users, conversion rate)

##  Tech Stack

Databricks
Apache Spark
Delta Lake
Python

##  Use Case

Real-time data processing for analytics (IoT / logs simulation).
I implemented data quality rules and optimized storage using partitioning in Unity Catalog.
I designed aggregated analytical tables with partitioning and computed KPIs like conversion rate for business insights.



## Sample KPIs
Total revenue per day
Active users
Event distribution
Conversion rate


Dashboard
<img width="690" height="400" alt="Daily Metrics Dashboard" src="https://github.com/user-attachments/assets/0482d418-426e-45e7-a96e-75cfe2d1bf74" />
<img width="690" height="450" alt="Event Distribution by Type" src="https://github.com/user-attachments/assets/67fba284-e6b9-4e55-9ef1-bd1ada158e1f" />
<img width="690" height="450" alt="Revenue Evolution Over Time" src="https://github.com/user-attachments/assets/babd7661-0895-445e-bac2-b06374f25762" />




## What I Learned
Designing scalable data pipelines
Handling streaming data
Implementing data quality checks
Building analytical layers for business
##  Status
Completed end-to-end pipeline

