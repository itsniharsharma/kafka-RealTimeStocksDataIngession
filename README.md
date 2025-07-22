# 📈 Real-Time Stock Market Data Engineering with Kafka & AWS

## 👋 About the Project

This is an **end-to-end real-time data engineering pipeline** I implemented to stream, store, catalog, and query live stock market data using **Apache Kafka** and **Amazon Web Services (AWS)**.  
The goal was to **build a robust data pipeline** capable of ingesting and analyzing stock prices in real time using modern cloud-native tools.

> Technologies explored: Kafka, AWS (EC2, S3, Glue, Athena), Python, and distributed data streaming.

---

## 🧱 Architecture Overview

![Architecture](Architecture.jpg)

The architecture involves:
- Streaming stock market data using **Kafka producers**
- Pushing the data to **AWS S3** via a **Kafka consumer**
- Using **AWS Glue Crawlers** to automatically catalog the data
- Running **SQL analytics** over the data using **AWS Athena**

---

## 🔧 Tech Stack

### Programming Language:
- **Python**

### Cloud Platform:
- **Amazon Web Services (AWS)**

### Services Used:
- **EC2** – Hosting Kafka producers and consumers
- **S3** – Storing real-time stock data in structured format
- **Glue Crawler** – Auto-detecting and cataloging schema
- **Glue Data Catalog** – Central metadata repository
- **Athena** – Serverless SQL queries on S3 data

### Streaming Tool:
- **Apache Kafka** – For real-time message queuing and streaming

---

## 💡 What I Learned

- Setting up a real-time Kafka pipeline on cloud infrastructure
- Managing data ingestion and batch organization on AWS S3
- Automating schema discovery using AWS Glue Crawlers
- Querying S3 data lakes using Athena + SQL
- Best practices for real-time data architecture and cost-efficient analytics

---

## 🚀 Future Scope

- Add real-time dashboards with Apache Superset or Grafana  
- Apply ML models for trend prediction  
- Streamline with Apache Airflow for orchestration  
- Add schema validation with Avro or Protobuf


