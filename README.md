
# 🔐 Real-Time Phishing Detection Platform

![Python](https://img.shields.io/badge/ML-Python-yellow?logo=python)
![Spark](https://img.shields.io/badge/ETL-Apache%20Spark-orange?logo=apachespark)
![Kafka](https://img.shields.io/badge/Streaming-Kafka-black?logo=apachekafka)
![MLflow](https://img.shields.io/badge/MLOps-MLflow-blue)
![Azure](https://img.shields.io/badge/Cloud-Azure-blue?logo=microsoftazure)
![Kubernetes](https://img.shields.io/badge/Deploy-Kubernetes-blue?logo=kubernetes)

---

## 📌 Introduction

Phishing attacks are one of the most widespread cybersecurity threats, targeting users through deceptive URLs and malicious websites.

This project presents a **real-time phishing detection system** that identifies suspicious URLs using machine learning and distributed data processing.

The system is designed for **scalability, low-latency inference, and production deployment in cloud environments**.

---

## 🧠 Skills Used

- Machine Learning (Unsupervised Learning)
- Isolation Forest for Anomaly Detection
- Feature Engineering for URL-based signals
- Distributed Data Processing (Apache Spark)
- Real-Time Data Streaming (Kafka)
- Backend API Development (Spring Boot / REST APIs)
- MLOps (MLflow Model Registry)
- Cloud Deployment (Azure Kubernetes Service)
- Data Visualization (Matplotlib / Seaborn)

---

## ⚙️ Project Overview

This system processes high-volume URL streams and detects phishing attempts in real time.

### 🔄 Pipeline Architecture

- Data ingestion via streaming pipelines (Kafka)
- Distributed ETL using Apache Spark
- Feature engineering (URL behavior analysis)
- Anomaly detection using Isolation Forest
- Model tracking with MLflow
- Real-time inference via REST API
- Deployment on Azure Kubernetes Service (AKS)

---

## 📊 Key Features Detected

The system focuses on detecting common phishing behaviors such as:

- IP-based URLs hiding malicious domains  
- URL shortening services  
- Subdomain manipulation  
- HTTPS misuse for spoofing trust  
- Long or suspicious domain registration patterns  
- Redirect-based obfuscation (`//` abuse)  

---

## ⚡ Performance Highlights

- Processed **500K+ URLs/day** using Spark pipelines  
- Achieved **low-latency real-time inference** via REST API  
- Reduced manual phishing review workload significantly  
- Enabled automated detection of unseen phishing patterns  

---

## 🤖 Machine Learning Approach

- Model: **Isolation Forest (Unsupervised Learning)**
- No labeled data required  
- Detects anomalies in URL feature space  
- Effective for evolving phishing strategies  

---

## 🏗️ System Architecture

```

Kafka (Streaming Ingestion)
↓
Apache Spark (Distributed ETL)
↓
Feature Engineering Layer
↓
Isolation Forest Model (MLflow)
↓
Spring Boot REST API
↓
Azure AKS (Kubernetes Deployment)
↓
Real-Time Alert System

```

---

## 📈 Insights

- URL structure is a strong signal for phishing detection  
- Attackers frequently exploit domain similarity and redirects  
- Unsupervised learning adapts better to evolving threats  
- Real-time pipelines are critical for production security systems  

---

## 🚀 Future Improvements

- Add deep learning-based URL/text classification  
- Integrate real-time threat intelligence feeds  
- Deploy dashboard for live phishing monitoring  
- Enhance streaming analytics with Kafka Streams / Flink  
- Improve explainability of anomaly predictions  

---

## 📬 Contact

Open to discussions on:

- Real-time ML systems  
- Cybersecurity engineering  
- Distributed data pipelines  
- Backend + ML production architecture  
```



