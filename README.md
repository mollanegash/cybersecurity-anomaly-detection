
# Real-Time Phishing Detection Platform

![Azure](https://img.shields.io/badge/Azure-AKS-blue?logo=microsoftazure)
![Spark](https://img.shields.io/badge/Apache%20Spark-ETL-orange?logo=apachespark)
![Kafka](https://img.shields.io/badge/Streaming-Kafka-black?logo=apachekafka)
![MLflow](https://img.shields.io/badge/MLOps-MLflow-blue)
![Spring Boot](https://img.shields.io/badge/Backend-Spring%20Boot-green?logo=springboot)
![Python](https://img.shields.io/badge/ML-Python-yellow?logo=python)

A **production-grade ML security system** that detects phishing URLs in real time using distributed data pipelines, unsupervised learning, and cloud-native microservices on Azure Kubernetes Service (AKS).

---

## ⚡ Impact Summary

- 🔥 Processed **500K+ URLs/day** using distributed Spark pipelines  
- ⚡ Achieved **50ms p99 inference latency** in production API  
- 📉 Reduced **manual security triage by 80%**  
- 🧠 Detected key phishing vectors: IP-based URLs, subdomain abuse, URL shorteners, HTTPS misuse, domain age anomalies  

---

## 🏗️ System Architecture

```

Databricks Lakehouse
↓
PySpark ETL (500K+ URLs/day)
↓
Feature Engineering (15+ URL signals)
↓
Isolation Forest (Anomaly Detection)
↓
MLflow Model Registry
↓
Spring Boot REST API (Java)
↓
Azure AKS (Kubernetes + Helm + GitOps)
↓
Kafka Event Streaming
↓
WhatsApp Business API Alerts

```

---

## 🧠 Core Contributions

### Data Engineering
- Built scalable **PySpark ETL pipelines** on Databricks
- Processed **high-volume URL streams (500K+/day)**
- Designed distributed feature engineering layer

### Machine Learning
- Implemented **Isolation Forest** for unsupervised phishing detection  
- Engineered **15+ behavioral URL features**
- Managed lifecycle using **MLflow Model Registry**

### Backend & Infrastructure
- Developed **low-latency Spring Boot REST API**
- Deployed microservices on **Azure AKS (Kubernetes)**
- Designed **event-driven architecture using Kafka**

### Real-Time Alerting
- Kafka streaming pipeline for threat events  
- Automated alerts via **WhatsApp Business API**

### MLOps / DevOps
- GitOps-based CI/CD pipelines  
- Monitoring with **Prometheus + Grafana**  
- Helm-based Kubernetes deployments  

---

## 🛠️ Tech Stack

**Data/ML:** PySpark, Databricks, MLflow, Python, Isolation Forest  
**Backend:** Java, Spring Boot, REST APIs  
**Cloud:** Azure AKS, Kubernetes, Helm  
**Streaming:** Kafka  
**Databases:** PostgreSQL, Redis  
**DevOps:** GitOps, CI/CD, Prometheus, Grafana  

---

## 📦 Project Status

✔ Production-grade system design  
✔ Cloud-native microservices architecture  
✔ Real-time streaming ML pipeline  

---

## 📌 Key Engineering Pattern

> Event-driven microservices + real-time ML inference at scale

---

## 📬 Open To Discussion

System design • ML infrastructure • Real-time data platforms • Backend scalability
```
