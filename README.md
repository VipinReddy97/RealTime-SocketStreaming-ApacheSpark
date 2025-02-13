# README

## Introduction

This project provides a **step-by-step guide** to building an **end-to-end data engineering pipeline** using **TCP/IP Socket, Apache Spark, OpenAI LLM, Kafka, and Elasticsearch**. It walks through every stage, starting from **data acquisition and processing**, applying **real-time sentiment analysis using ChatGPT**, and finally **publishing the results to Kafka** while **integrating Elasticsearch for indexing and querying**.

---

## System Architecture

![System Architecture](media/System_architecture.png) 

The project is designed with the following components:

- **Data Source**: We use `yelp.com` dataset for our pipeline.
- **TCP/IP Socket**: Streams data over the network in chunks.
- **Apache Spark**: Handles data processing using master and worker nodes.
- **Confluent Kafka**: Managed Kafka cluster on the cloud.
- **Control Center and Schema Registry**: Enables Kafka monitoring and schema management.
- **Kafka Connect**: Connects Kafka with Elasticsearch.
- **Elasticsearch**: Stores and indexes data for efficient querying.

---

## **Things We Will Be Working On**
- Setting up a **data pipeline with TCP/IP**.
- Implementing **real-time data streaming with Apache Kafka**.
- Utilizing **Apache Spark** for distributed data processing.
- Performing **sentiment analysis with OpenAI ChatGPT**.
- Synchronizing **Kafka data with Elasticsearch**.
- **Indexing and querying** data using Elasticsearch.

---

## **Technologies**
- Python
- TCP/IP
- Confluent Kafka
- Apache Spark
- Docker
- Elasticsearch

---

## **Getting Started**
### **1. Clone the Repository**
```sh
git clone https://github.com/VipinReddy97/RealTime-SocketStreaming-ApacheSpark.git
```
### **2. Navigate to the Project Directory
```sh
cd RealTime-SocketStreaming-ApacheSpark
```
### **3. Run Docker Compose to Spin Up the Spark Cluster
```sh
docker-compose up
```
