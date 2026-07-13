# 📊 ELK Stack with Docker

A Dockerized ELK Stack (Elasticsearch, Logstash, and Kibana) developed as part of a Cloud Computing coursework assignment. This project demonstrates centralized log collection, indexing, and visualization using Docker Compose.

---

## 📖 Overview

The ELK Stack is widely used for log management and data visualization. This project deploys Elasticsearch, Logstash, and Kibana as separate Docker containers that communicate using Docker Compose.

---

## ✨ Features

- Elasticsearch for data indexing
- Logstash for log processing
- Kibana dashboard
- Docker Compose deployment
- Sample log ingestion
- Centralized logging

---

## 🛠 Technologies

- Docker
- Docker Compose
- Elasticsearch
- Logstash
- Kibana

---

## 📂 Project Structure

```
elk-stack-docker/
│
├── docker-compose.yml
├── README.md
├── logstash/
│   └── logstash.conf
└── sample-data/
    └── sample.log
```

---

## 🚀 Run

Build & Start

```bash
docker-compose up
```

Stop

```bash
docker-compose down
```

---

## 🌐 Access

Elasticsearch

```
http://localhost:9200
```

Kibana

```
http://localhost:5601
```

---

## 📚 Learning Outcomes

- Docker Networking
- ELK Architecture
- Log Aggregation
- Data Visualization
- Container Orchestration

---

## 👩‍💻 Author

**Tehzeeb Masood**

GitHub: https://github.com/tahzzzeebbb
