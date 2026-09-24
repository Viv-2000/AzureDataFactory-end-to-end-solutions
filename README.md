# Azure Data Factory — End-to-End Solutions

Hands-on data engineering projects built with **Azure Data Factory** and **Azure Data Lake Storage Gen2**, version-controlled through ADF's GitHub integration.

## Projects

| Project | Summary | Key features |
|---|---|---|
| [NASA Near-Earth Object Pipeline](./Nasa%20Data%20Engineering%20Solutions/) | Event-driven pipeline that ingests NASA asteroid data from an HTTP source, routes files dynamically, and produces a curated dataset of hazardous asteroids | Storage event trigger, parameterised datasets, Get Metadata → ForEach → If Condition, idempotent clean-up, pipeline orchestration, Mapping Data Flows, null profiling |

## Tech stack

Azure Data Factory · ADLS Gen2 · Mapping Data Flows · Azure Event Grid · GitHub

## Coming next

An aged care operations data platform: metadata-driven ingestion in ADF feeding an Azure Databricks medallion lakehouse (Delta Lake, PySpark) and Power BI.
