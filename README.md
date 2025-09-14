# Overview

This project demonstrates a modern real-time data processing pipeline built with open-source technologies. The architecture is designed for scalability, fault tolerance, and high throughput, making it suitable for handling large volumes of streaming data.

The system integrates data ingestion, orchestration, streaming, processing, and storage, providing a robust foundation for advanced analytics and machine learning use cases.

# 🏗️ Architecture

# Components

- API – Entry point for ingesting raw data into the pipeline.

- Apache Airflow – Orchestrates workflows and manages scheduling.

- PostgreSQL – Stores metadata and transactional data.

- Apache Kafka – Core event streaming platform enabling high-throughput, low-latency messaging.

- ZooKeeper – Coordinates and manages Kafka brokers.

- Control Center – Provides monitoring and management of Kafka clusters.

- Schema Registry – Manages schemas for Kafka topics, ensuring data compatibility.

- Apache Spark (Master & Workers) – Processes streaming data in parallel for analytics and transformations.

- Cassandra – Highly scalable NoSQL database for storing processed results.

- Docker – Containerization to ensure consistency, scalability, and portability.



# 🚀 Getting Started
# Prerequisites

- Docker

- Apache Airflow

- Apache Kafka

- Apache Spark

- Cassandra
