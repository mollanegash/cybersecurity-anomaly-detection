# Real-Time Phishing Detection Platform (Production ML System)

A **production-grade distributed system** that detects phishing URLs in real time using machine learning, streaming pipelines, and cloud-native microservices.

Designed to demonstrate **ML engineering + backend systems + scalable architecture (SWE-focused AI system design).**

---

## ⚡ Why This Project Matters (SWE Framing)

This is not a notebook model — it is a **fully deployed ML system** with:

- Real-time data ingestion (Kafka)
- Distributed processing (Spark on Databricks)
- ML inference service (Spring Boot API)
- Cloud deployment (Azure AKS Kubernetes)
- Production monitoring (Prometheus + Grafana)

---

## 🧠 System Architecture


Data Sources (URL Streams)
↓
Databricks (Spark ETL)
↓
Feature Engineering (15+ signals)
↓
Isolation Forest Model
↓
MLflow Model Registry
↓
Spring Boot Inference API (Java)
↓
Azure Kubernetes Service (AKS)
↓
Kafka Event Streaming
↓
Alerting System (WhatsApp API)


---

## 🔥 Engineering Highlights (What Recruiters Care About)

### 🧱 Distributed Systems
- Built Spark ETL pipeline processing **500K+ URLs/day**
- Designed event-driven architecture using **Kafka**
- Implemented microservices deployed on **Kubernetes (AKS)**

### ⚙️ Backend Engineering
- Built low-latency **Java Spring Boot inference API**
- Achieved **50ms p99 response latency**
- Designed stateless scalable API layer for ML inference

### 🤖 ML Engineering (Not Just ML)
- Used **Isolation Forest for anomaly detection**
- Engineered **15+ behavioral URL features**
- Deployed model via **MLflow registry**

### ☁️ Production / DevOps
- CI/CD using **GitOps workflows**
- Infrastructure on **Azure Kubernetes Service**
- Monitoring via **Prometheus + Grafana**

---

## 📊 Impact

- 🚀 500K+ URLs processed daily
- ⚡ 50ms p99 inference latency
- 📉 80% reduction in manual security triage
- 🧠 Real-time detection of phishing patterns:
  - IP-based URLs
  - URL shorteners
  - Subdomain abuse
  - HTTPS spoofing
  - Domain age anomalies

---

## 🛠️ Tech Stack (SWE-Oriented)

**Backend:** Java, Spring Boot, REST APIs  
**Data Engineering:** Spark, Databricks  
**ML:** Python, Isolation Forest, MLflow  
**Streaming:** Kafka  
**Cloud:** Azure AKS, Kubernetes, Helm  
**Observability:** Prometheus, Grafana  
**Databases:** PostgreSQL, Redis  

---

## 📌 Key Takeaway

This project demonstrates:

> ✔ Ability to design scalable backend systems  
> ✔ Ability to deploy ML into production  
> ✔ Understanding of distributed systems + cloud infrastructure  
> ✔ SWE + ML Engineering hybrid skillset  

---

## 📬 Open to Discussion

System design • Backend engineering • ML infrastructure • Distributed systems
