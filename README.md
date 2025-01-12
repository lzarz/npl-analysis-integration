# Non-Performing Loan (NPL) Analysis integration

![Supported Python Versions](https://img.shields.io/badge/python-3.8%2B-0D7FBF)
![Ubuntu](https://img.shields.io/badge/linux-compatible-40CA22)
![Windows](https://img.shields.io/badge/windows-compatible-40CA22)

## Overview

This project demonstrates the integration of a data pipeline for Non-Performing Loan (NPL) analysis using a modern data architecture. The pipeline orchestrates the extraction, transformation, and loading (ETL) processes across various systems to enable efficient data processing and analysis.

Key components include:

- Data Sources: Structured loan data stored in MongoDB (NoSQL) and PostgreSQL (RDBMS).
- Data Streaming: Apache Kafka enables real-time data streaming for transactional data changes.
- ETL Orchestration: Apache Airflow orchestrates the pipeline workflows and dependencies.
- Data Transformation: Talend and Apache Spark are used to clean, transform, and process the data.
- Data Storage: Processed data is stored in Amazon Redshift (OLAP) for analytical queries and in Hadoop Distributed File System (HDFS) for scalable data storage.
- Data Analysis: Power BI is utilized for visualizing and generating insights from the NPL metrics.

## Scenario

A bank wants to analyze its Non-Performing Loan (NPL) portfolio across multiple branches. The data is collected from transactional systems (MongoDB and PostgreSQL) that store loan records and repayment details. To enable timely decision-making, the bank requires the following:

1. Daily NPL Metrics: Compute NPL amounts for each branch, identifying overdue loans.
2. Real-Time Insights: Use Apache Kafka to stream loan updates and repayments in real time.
3. Data Processing: Transform raw loan data into meaningful insights, such as overdue trends, using Talend and Apache Spark.
4. Scalable Storage: Store processed data in Amazon Redshift for OLAP queries and Hadoop for long-term storage.
5. Interactive Dashboards: Use Power BI to generate visualizations, such as overdue trends, branch-wise NPL performance, and recovery ratios.

The orchestrated pipeline ensures timely data availability for decision-making and supports scalability to handle increasing data volumes.

## Architecture

The interpretation of the pipeline architecture:

<p align="center"><img src=https://raw.githubusercontent.com/lzarz/npl-analysis-integration/refs/heads/main/npl-analysis-pipeline.svg?sanitize=true"></p>

The architecture ensures scalability, real-time data processing, and comprehensive reporting capabilities.

## Dataset and Analysis

Soon!

## Requirements

- MongoDB
- PostgreSQL
- Talend
- Kafka
- Apache Spark
- Apache Airflow
- Amazon Redshift
- Apache Hadoop
- Power BI

## Schema

Soon!

## Set-up

Soon!

## Installation

Soon!
