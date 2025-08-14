# Kafka with PySpark Structured Streaming

This project demonstrates how to **write data to Kafka** from a CSV source using PySpark Structured Streaming and **read data from Kafka** back into Spark for processing.

## 📂 Files
- **write_to_kafka.py** → Reads streaming CSV files from a folder and writes them to a Kafka topic.
- **read_from_kafka.py** → Reads messages from a Kafka topic and prints them to the console.

---

## ⚙️ Prerequisites

1. **Apache Kafka** installed and running.
2. **Apache Spark** with Kafka connector.
3. **Python 3.x** and required packages:
