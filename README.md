# 🏥 Modern Data Platform for MeddGGenius  
*A Cloud-Based Data Lakehouse Solution*

This repository contains Group 2’s final project for the course **BUAN 6335.502 – Organizing for Business Analytics Platforms** at UT Dallas. The project proposes a comprehensive data lakehouse architecture for **MeddGGenius**, a regional healthcare provider aiming to modernize its data infrastructure using AWS cloud services.

## 💡 Problem Statement

MeddGGenius is struggling with:
- Legacy RDBMS and Teradata systems
- Disconnected data silos
- High costs and limited scalability
- Inability to process real-time and unstructured data (e.g., IoT, medical imaging)

## 🎯 Project Goals

- Create a unified platform for OLTP and OLAP workloads
- Support structured and unstructured data (EHRs, IoT, images)
- Enable real-time analytics and machine learning
- Ensure HIPAA and NIST compliance

---

## 🧱 Proposed Architecture – AWS Data Lakehouse

### 🔹 Key Components:
- **Storage & Ingestion**: S3, Kinesis, DataSync
- **Transformation**: AWS Glue
- **Analytics**: Athena, SageMaker
- **Visualization**: QuickSight
- **Security**: IAM, Lake Formation, KMS, CloudTrail
- **Monitoring**: CloudWatch

### 🔄 Data Flow:
1. Data from EHRs, IoT, images, and APIs ingested into S3
2. AWS Glue handles ETL and schema discovery
3. Athena and SageMaker support analytics and ML
4. Dashboards created in QuickSight for decision-making
5. Security and compliance managed via IAM, KMS, and audit logs

---

## 📊 Machine Learning Use Cases

- **Medical Imaging**: Deep learning for X-ray and MRI diagnostics
- **Preventive Care**: Predictive models from vitals data
- **Patient Monitoring**: Real-time risk tracking using IoT sensor streams

---

## 🔐 Compliance & Security

- End-to-end encryption (KMS)
- Role-based access control (IAM)
- HIPAA-compliant architecture
- Continuous monitoring and audit logging (CloudWatch, CloudTrail)

---

## 🧭 Execution Roadmap

- Assessment → ETL Pipeline Design → Validation → Migration  
- Data retention via S3 tiers (Standard, Infrequent, Glacier)
- Continuous feedback loops and progress tracking

---

## ✅ Key Benefits

- Unified patient data access
- Enhanced care delivery with ML insights
- Reduced operational costs and system lag
- Scalable infrastructure to support innovation

---

## 👥 Team – Group 2

- Adithya Ramakrishnan  
- Eunsung Choi  
- Jurgen Wulur  
- Kartik Shah  
- Prasanth Chowdary Yanamandala  
- Richard Yang  
- Tanmay Raju Shedge

---

📌 *This project illustrates how a modern, secure, and scalable cloud-based data lakehouse can transform healthcare analytics and patient outcomes.*
