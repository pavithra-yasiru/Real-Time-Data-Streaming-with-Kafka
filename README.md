# 📡 Real-Time Kafka Producing & Consuming with Confluent Kafka Cloud  
### 🧩 Python | Jupyter Notebooks | Confluent Cloud | Real-Time Streaming

This project demonstrates **real-time message streaming** using **Apache Kafka** hosted on **Confluent Kafka Cloud**.  
It includes:

- ✔️ A Kafka **Producer** notebook (`Kafka Producer.ipynb`)  
- ✔️ A Kafka **Consumer** notebook (`Kafka Consumer.ipynb`)  
- ✔️ A dataset used for streaming (`first_100_customers.csv`)  
- ✔️ A real-time demo video showing produce & consume (`Kafka Producing & Consuming.mp4`)

Perfect for anyone learning real-time event streaming and cloud-based Kafka pipelines. 🚀

## 📁 Project Structure
├── Kafka Producer.ipynb
├── Kafka Consumer.ipynb
├── first_100_customers.csv
└── Kafka Producing & Consuming.mp4 (demo video)

## 🏗️ **Project Overview**

This project simulates **real-time customer events** being published and consumed via Kafka on **Confluent Cloud**.

### 🔹 **Producer Notebook**
The producer:

- Reads the dataset **`first_100_customers.csv`**
- Converts each row to a JSON message  
- Publishes messages to a Confluent Kafka topic  
- Uses delivery callbacks  
- Ensures message acknowledgements

### 🔹 **Consumer Notebook**
The consumer:

- Connects to the same Kafka topic  
- Continuously polls for messages  
- Decodes and prints real-time streaming events  
- Demonstrates reliable, low-latency consumption  

## 🧪 **Dataset: `first_100_customers.csv`**

The dataset contains customer records used as the streaming source.  
Each row is turned into a Kafka message by the producer.

## 🎥 **Demo (Screen Recording)**

The screen recording **“Kafka Producing & Consuming”** shows:

- Left side ➝ Kafka Producer sending messages  
- Right side ➝ Kafka Consumer receiving them in real-time  

This visually demonstrates the full streaming pipeline working live. ⚡

## ☁️ **Confluent Kafka Cloud Setup (Summary)**

The notebooks assume the following were already configured:

1. A Confluent Kafka Cluster  
2. Created a topic (e.g., `customer-stream`)  
3. API Key & Secret  
4. Bootstrap Server URL  
5. Installed required dependencies:
   ```bash
   pip install confluent-kafka pandas
   Environment variables / configs are loaded inside the notebooks.

## 🛠️ Technologies Used

Python
Jupyter Notebook
Confluent Kafka Cloud
Apache Kafka
Pandas

## 👤 Author
Pavithra Yasiru

