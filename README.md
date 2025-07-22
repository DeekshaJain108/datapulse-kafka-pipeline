# datapulse-kafka-pipeline
This project implements a real-time data pipeline using Apache Kafka, Python's psutil library for metric collection, and SQL Server for data storage. The pipeline collects metrics data from the local computer, processes it through Kafka brokers, and loads it into a SQL Server database. Additionally, a real-time dashboard is created using Power BI.

## Project Overview
This project implements a real-time data pipeline using Apache Kafka, Python's psutil library for metric collection, and SQL Server for data storage. The pipeline collects metrics data from the local computer, processes it through Kafka brokers, and loads it into a SQL Server database. Additionally, a real-time dashboard is created using Power BI, providing a user-friendly interface for monitoring the collected metrics.

## Technologies Used
Python: Utilized the psutil library for collecting metrics data and Kafka Python client for producing and consuming messages.
Apache Kafka: Implemented a distributed streaming platform to handle real-time data processing and communication between producers and consumers.
Apache Zookeeper: Used for coordinating and managing Kafka brokers.
SQL Server: Stored and managed the collected metrics data in a relational database.
Power BI: Connected to the SQL Server database to visualize real-time metrics and create the dashboard.

## Data Pipeline
The data pipeline consists of the following steps:

Data Collection: Metrics data is collected from the local computer using the psutil Python library.
Data Production: The collected data is sent as messages to Kafka topics through a Kafka producer.
Data Consumption: Kafka consumers read the messages from the topics, process them, and load the data into SQL Server.
Dashboard Creation: Power BI connects to the SQL Server database and creates a real-time dashboard for monitoring the metrics data.


