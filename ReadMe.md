## Realtime-Data-Streaming-API

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage, utilizing a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. Everything is containerized using Docker for ease of deployment and scalability.

![Data engineering architecture.png](..%2F..%2FOneDrive%2FDesktop%2FDecember%20Plan%28Data%20Engineering%29%2FRealtime%20Data%20Streaming%20%20End%20To%20End%20Data%20Engineering%20Project-API-cassandra%2FData%20engineering%20architecture.png)

The project is designed with the following components:

Data Source: We use randomuser.me API to generate random user data for our pipeline.
Apache Airflow: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
Apache Kafka and Zookeeper: Used for streaming data from PostgreSQL to the processing engine.
Control Center and Schema Registry: Helps in monitoring and schema management of our Kafka streams.
Apache Spark: For data processing with its master and worker nodes.
Cassandra: Where the processed data will be stored.