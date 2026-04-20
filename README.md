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
<img width="690" height="450" alt="newplot" src="https://github.com/user-attachments/assets/15d2193a-f80a-4d2c-b370-be68d38ea8f0" />
<img width="690" height="450" alt="newplot" src="https://github.com/user-attachments/assets/205b659e-4c9d-406a-b190-9bfc781a4018" />
<img width="690" height="400" alt="newplot (1)" src="https://github.com/user-attachments/assets/826880e3-3fbd-4c04-a329-8fafb9b73274" />
<img width="690" height="450" alt="newplot (2)" src="https://github.com/user-attachments/assets/73c16f8e-f199-4ec9-8379-5625bef0a29a" />
<img width="690" height="400" alt="newplot (1)" src="https://github.com/user-attachments/assets/8e95d75b-4fbd-4a16-8729-f66b6c0ecb2d" />



## What I Learned
Designing scalable data pipelines
Handling streaming data
Implementing data quality checks
Building analytical layers for business
##  Status
Completed end-to-end pipeline

