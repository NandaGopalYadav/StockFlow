# KafkaStockStreamer 🚀


**KafkaStockStreamer** is a real-time stock market data simulation pipeline built using **Apache Kafka** and **Python**. It emulates a production-grade event streaming platform that can be used for learning, demonstrations, or building upon with real datasets.

---

## 💡 Project Motivation

In an era where data moves faster than ever, real-time streaming systems have become essential. KafkaStockStreamer was created as a foundational project for understanding and deploying scalable, event-driven architectures. This repository serves as a launchpad for real-time analytics, stock data simulation, and distributed stream processing.

---

## 🔧 Features

- 📊 **Real-Time Data Ingestion** — Stream mock stock prices into Kafka topics
- 🎧 **Consumer Logic with Offset Management** — Reliable, replayable stream consumption
- 🧱 **Modular & Scalable** — Easy to extend, deploy, and integrate with AWS
- 📜 **Clean Python Scripts** — Clear separation of producer, consumer, and utilities
- ☁️ **Cloud-Ready** — Can be hosted on EC2 and connected with Athena/S3/Glue pipelines

---

## 🛠️ Tech Stack

| Technology    | Usage                         |
|---------------|-------------------------------|
| **Apache Kafka** | Distributed stream processing |
| **Python**       | Producer/consumer scripting   |
| **JMESPath**     | Optional filtering/querying   |
| **AWS EC2**      | Hosting Kafka brokers         |
| **Amazon S3/Athena** | (Future integration)      |

---

## ⚙️ Getting Started

```bash
# Start Kafka and Zookeeper

# Run Producer
python Scripts/producer_v2.py

# Run Consumer
python Scripts/consumer_v2.py
```

You can also follow instructions in `initial_setup.txt` to configure Kafka on AWS EC2 and simulate a production setup.

---

## 📁 Project Structure

```
KafkaStockStreamer/
├── Scripts/
│   ├── producer_v2.py
│   ├── consumer_v2.py
│   ├── jp.py
│   ├── pywin32_postinstall.py
│   ├── pywin32_testall.py
├── assets/
│   └── architecture_diagram.png
├── initial_setup.txt
├── LICENSE
└── README.md
```

---

## ✨ Author

**Nanda Gopal Yadav Pattapagalu**  
*Cloud-native developer & real-time data pipeline enthusiast.*  
📬 [LinkedIn](https://www.linkedin.com/in/nanda-gopal-yadav-pattapagalu/) | 🌐 [Website](https://nandagopalyadav.github.io/#)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

