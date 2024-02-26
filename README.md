
# Realtime Data Streaming | End-to-End Data Engineering Project

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

## Introduction

Welcome to the Realtime Data Streaming project, ultimate guide to constructing a robust end-to-end data engineering pipeline. This project covers every aspect of the data lifecycle, from ingestion to processing and storage, employing a powerful tech stack comprising Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, Cassandra, and Docker for seamless deployment and scalability.

## System Architecture

![System Architecture](https://github.com/airscholar/e2e-data-engineering/blob/main/Data%20engineering%20architecture.png)

The project is meticulously crafted with the following components:

- **Data Source**: Utilizing the `randomuser.me` API to generate diverse user data for our pipeline.
- **Apache Airflow**: Serving as the orchestrator, Airflow manages the workflow and stores fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Facilitating seamless data streaming from PostgreSQL to the processing engine for high throughput and fault tolerance.
- **Control Center and Schema Registry**: Essential tools for monitoring and schema management of Kafka streams, ensuring data integrity.
- **Apache Spark**: Empowering data processing with its distributed computing capabilities, utilizing master and worker nodes.
- **Cassandra**: Providing scalable storage for processed data, ensuring high availability and efficiency.

## Syllabus

Explore the following topics in-depth as part of this project:

- Setting up a data pipeline with Apache Airflow
- Real-time data streaming with Apache Kafka
- Distributed synchronization with Apache Zookeeper
- Data processing techniques with Apache Spark
- Data storage solutions with Cassandra and PostgreSQL
- Containerizing your entire data engineering setup with Docker

## Technologies

This project leverages cutting-edge technologies to deliver a robust data engineering solution:

- Apache Airflow: Orchestration and workflow management
- Python: Programming language for building data pipelines
- Apache Kafka: Distributed streaming platform
- Apache Zookeeper: Distributed coordination service
- Apache Spark: Distributed computing engine
- Cassandra: NoSQL database for scalable storage
- PostgreSQL: Relational database for structured data storage
- Docker: Containerization for seamless deployment and scalability

## Getting Started

Follow these simple steps to kickstart your journey with the Realtime Data Streaming project:

1. **Clone the repository**:
```bash
git clone https://github.com/airscholar/e2e-data-engineering.git-----------
```

2. **Navigate to the project directory**:
```bash
cd e2e-data-engineering
```

3. **Run Docker Compose to spin up the services**:
```bash
docker-compose up
```

