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


## What I Learned
Designing scalable data pipelines
Handling streaming data
Implementing data quality checks
Building analytical layers for business
##  Status
Completed end-to-end pipeline

