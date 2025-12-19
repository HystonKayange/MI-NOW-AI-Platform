#  MI-NOW - Enterprise Business Intelligence Platform

<div align="center">



**Enterprise-grade BI platform with advanced ETL pipelines and RAG capabilities for Korean manufacturing data**

</div>

---

## 📊 Project Overview

Deployed an enterprise Business Intelligence platform delivering **ETL and RAG APIs** for Korean manufacturing and global industrial data, featuring intelligent data processing, AI-powered search, and comprehensive system monitoring.

## ✨ Key Achievements

- 🎯 **High-Performance RAG**: Achieved **97.7% precision**, **70.0% recall**, **82.3% F1 score** with only **12.4% hallucination rate**
- 📈 **Large-Scale Data Processing**: Successfully processed **39,000+ ETL jobs** with **99% success rate**
- 🔄 **Zero-Downtime Architecture**: Dual-provider AI system with automated failover between on-premise and cloud LLMs
- 🔒 **Enterprise Security**: Multi-tenant isolation with role-based access control (RBAC)
- 🌏 **Korean Language Optimized**: Specialized NLP pipeline for Korean manufacturing terminology

## 🏗️ Technical Implementation

**ETL Pipeline**
- Scalable data ingestion from Korean manufacturing websites and enterprise documents
- OCR support using Tesseract.js for image and scanned document processing
- Automated job scheduling with BullMQ and Redis queue management
- Real-time monitoring with comprehensive metrics and analytics

**Hybrid RAG System**
- Combined semantic search, keyword matching, and file-based retrieval
- Dual-provider AI inference: On-premise **Ollama** (primary) + **CLOVA Studio** (fallback)
- Automated health checks and intelligent failover mechanism
- Vector storage with **Qdrant** for semantic search capabilities

**System Architecture**
- **Backend**: Node.js, TypeScript, Express.js
- **Frontend**: Next.js, React with modern dashboard UI
- **Databases**: AWS RDS (MySQL), Qdrant (Vector DB), AWS OpenSearch
- **Cloud**: AWS (S3, RDS, OpenSearch)
- **Caching & Queue**: Redis, BullMQ
- **AI/ML**: Ollama, CLOVA Studio, Tesseract.js

## 📸 Platform Screenshots

<div align="center">

### Dashboard Overview
![Dashboard](./Images/Dashboard.png)
*Real-time ETL monitoring with job trends and status distribution*

### ETL Pipeline Management
![ETL Management](./Images/ETL.png)
*Comprehensive pipeline management showing 38,854 completed jobs*

### RAG Analytics
![RAG Analytics](./Images/Rag_analytics1.png)
*AI performance metrics: 97.2% precision, 70% recall, 82.3% F1 score*

### Interactive RAG Chat
![RAG Chat](./Images/RAG_test.png)
* RAG chat interface with Model Selector (Ollsma Models)*

### ETL Scheduler
![Scheduler](./Images/Schedular.png)
*Day/Night mode scheduling with queue management*

### AI Model Settings
![Settings](./Images/Settings.png)
*Multi-model configuration with Ollama and Clova providers*

### System Health Monitoring
![System Health](./Images/System_health.png)
*Live monitoring of all services including MySQL, Qdrant, Admin Panel, and Ollama*

### User Behavior Analytics
![User Behavior](./Images/User_behaviour.png)
*Search trends and engagement metrics with 100% engagement rate*

### Vector Database Management
![Vectors](./Images/Vectors.png)
*Qdrant vector database with 31,410 indexed documents*

</div>

## 🎯 Impact & Results

| Metric | Result |
|--------|--------|
| **ETL Jobs Processed** | 39,427 total |
| **Success Rate** | 99%+ |
| **Documents Indexed** | 31,410 vectors |
| **RAG Precision** | 97.7% |
| **RAG F1 Score** | 82.3% |
| **Hallucination Rate** | 12.4% |
| **System Uptime** | 99.9% |

## 🔧 Core Features

- ✅ Multi-source data ingestion with OCR support
- ✅ Hybrid RAG with semantic + keyword search
- ✅ Dual-provider AI with automatic failover
- ✅ Multi-tenant architecture with RBAC
- ✅ Real-time monitoring dashboard
- ✅ Automated health checks and alerting
- ✅ Korean language optimization
- ✅ Comprehensive audit logging

---


