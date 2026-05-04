# 🔐 Phishing Detection Using Machine Learning

![Python](https://img.shields.io/badge/ML-Python-yellow?logo=python)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Security](https://img.shields.io/badge/Cybersecurity-Phishing-red)

## 📌 Introduction

Phishing attacks remain one of the most common cybersecurity threats, affecting millions of users worldwide through deceptive websites and malicious URLs.

This project demonstrates a **machine learning-based phishing detection system** that identifies suspicious URLs using anomaly detection techniques.

The goal is to build a lightweight and scalable approach for detecting phishing behavior using URL-based features.

---

## 🧠 Skills Used

- Machine Learning (Unsupervised Learning)
- Isolation Forest for Anomaly Detection
- Data Analysis & Feature Engineering
- Data Visualization
- Python Programming (Scikit-learn, Pandas, Matplotlib)

---

## ⚙️ Project Overview

This project uses the **Phishing Website Dataset** to detect malicious patterns in URLs.

### Pipeline:
- Data preprocessing and cleaning  
- Feature selection and engineering  
- Model training using Isolation Forest  
- Anomaly detection for phishing identification  
- Visualization of key security indicators  

---

## 📊 Key Findings

- **Most important indicator:**
  - Using IP address in URL to hide suspicious content  
  - Mean anomaly score: **0.5371**

- **Top phishing indicators:**
  - IP-based URLs  
  - Multiple subdomains  
  - HTTPS misuse in URL structure  
  - Long domain registration patterns  
  - URL shortening services  
  - Redirect patterns (`//` misuse)  

---

## 🤖 Model Performance

- Isolation Forest effectively detected anomalies without labeled data  
- Strong performance in identifying hidden phishing patterns  
- Demonstrates the effectiveness of unsupervised learning in cybersecurity  

---

## 📈 Insights

- URL structure is a strong predictor of phishing behavior  
- Attackers commonly manipulate domains and redirects  
- Unsupervised learning is effective when labeled data is limited  

---

## 🚀 Project Highlights

- Lightweight anomaly detection system  
- No dependency on labeled datasets  
- Suitable for real-time phishing detection systems  
- Strong baseline for cybersecurity ML applications  

---

## 📌 Future Improvements

- Integrate real-time URL scanning API  
- Deploy model as a REST API (FastAPI/Spring Boot)  
- Add streaming detection (Kafka-based pipeline)  
- Improve feature engineering with NLP-based URL analysis  

---

## 📬 Contact

Open to discussions on:
- Machine learning systems
- Cybersecurity analytics
- Real-time data pipelines
- Backend + ML integration
