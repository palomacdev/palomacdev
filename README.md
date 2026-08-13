# Hi, I'm Paloma Cordeiro 👋

### Tech Lead · Software Engineer · Data & ML Systems

I design and build **production-grade software systems** across data engineering, APIs, distributed architectures, machine learning, and MLOps.

I'm currently working as a **Tech Lead**, combining hands-on software development with technical leadership, architecture decisions, engineering standards, and delivery of production systems.

My engineering background is strongly rooted in **data and machine learning**, but my work goes beyond models and pipelines — I build the software infrastructure that makes complex systems reliable, scalable, and maintainable.

> **I don't just build software. I design the systems that make software work.**

---

## ⚡ What I Do

```text
┌─────────────────────────────────────────────────────────────┐
│                         TECH LEAD                           │
│                                                             │
│  Architecture · Technical Decisions · Engineering Quality   │
│  Mentorship · Delivery · System Design · Problem Solving    │
└──────────────────────────────┬──────────────────────────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
       ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
       │   Software   │ │     Data     │ │      ML      │
       │  Engineering │ │ Engineering  │ │   & MLOps    │
       └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
              │                │                │
              └────────────────┼────────────────┘
                               ▼
                    Production Systems
```

I work across the entire engineering lifecycle:

* System architecture and technical design
* Backend and API development
* Data pipelines and distributed processing
* Machine learning systems
* MLOps and model lifecycle
* Database architecture
* Infrastructure and containerization
* Technical leadership and engineering standards

---

# 🚀 Featured Projects

## 🏎️ DRS Data — Motorsport Analytics & Simulation Platform

**Python · XGBoost · Scikit-learn · SHAP · FastF1 · Pandas**

A motorsport analytics platform combining **data engineering, machine learning, statistical analysis, and race simulation** to model Formula 1 performance.

### Engineering

* End-to-end data ingestion and transformation pipelines
* Custom feature engineering for temporal and motorsport data
* Modular ML architecture
* Model evaluation and experiment comparison
* Explainability with SHAP
* Race simulation and scenario modeling
* Data-driven strategy analysis

### Machine Learning

* Qualifying grid prediction with ~3 position MAE
* XGBoost selected through comparative model evaluation
* Driver and team performance modeling
* Tire degradation and race strategy modeling
* Continuous model validation and recalibration

🔗 **[GitHub](https://github.com/palomacdev/drs_data)**

---

## 🏁 OpenWEC — Endurance Racing Data Platform

**Python · FastAPI · PostgreSQL · aiohttp · Playwright · Docker**

An open-source data platform for **FIA World Endurance Championship** data.

Built to provide a reusable engineering layer for endurance racing analytics, similar in spirit to the ecosystem around FastF1.

### Architecture

```text
WEC Data Sources
       │
       ▼
┌─────────────────┐
│ Data Discovery  │
│   & Cataloging  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Async Ingestion │
│     aiohttp     │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Data Processing │
│   & Validation  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   PostgreSQL    │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│    FastAPI      │
│       API       │
└─────────────────┘
```

### Highlights

* Automated historical session discovery
* Asynchronous high-performance data collection
* Reverse engineering of modern web data sources
* Structured season, event, session, classification, and stint datasets
* PostgreSQL data architecture
* REST API for programmatic access
* Designed as an extensible open-source data platform

🔗 **[openwec.com](https://openwec.com)**
🔗 **[GitHub](https://github.com/palomacdev/openwec)**

---

## ⚡ Real-Time Fraud Detection Platform

**Apache Kafka · Spark Structured Streaming · PySpark · MLflow · Docker Compose**

An end-to-end distributed streaming architecture for real-time fraud detection.

```text
Event Producer
      │
      ▼
    Kafka
      │
      ▼
Spark Structured Streaming
      │
      ├── Feature Engineering
      │
      └── ML Inference
              │
              ▼
           MLflow
```

### Highlights

* Real-time event ingestion with Kafka
* Distributed processing using Spark Structured Streaming
* Feature engineering inside the streaming pipeline
* ML inference on streaming data
* Fraud detection optimized for **96% recall**
* ROC-AUC improved from **0.53 → 0.77**
* Experiment and model tracking with MLflow
* Fully reproducible Docker Compose environment
* Domain-oriented service architecture

🔗 **[GitHub](https://github.com/palomacdev/ml-lab)**

---

## 🎤 OpenF1 Transcribe — Audio Processing Platform

**FastAPI · OpenAI Whisper · MongoDB · Docker Compose**

A distributed audio-processing platform that transforms Formula 1 team radio into searchable structured data.

### Highlights

* Microservices architecture
* FastAPI service layer
* Asynchronous audio processing
* OpenAI Whisper transcription
* MongoDB indexing and full-text search
* Thousands of audio files processed
* ~2.2s average processing time per audio file
* <50ms API response latency
* Containerized development environment
* Modular and maintainable codebase

🔗 **[GitHub](https://github.com/palomacdev/openf1-transcribe)**

---

# 🧩 Engineering Philosophy

I believe good engineering is not about choosing the most sophisticated technology.

It's about choosing the **right architecture for the problem**.

My approach focuses on:

* **Simplicity before unnecessary complexity**
* **Clear system boundaries**
* **Observable and testable services**
* **Reliable data flows**
* **Reproducible environments**
* **Automation over manual processes**
* **Designing for maintainability**
* **Measuring systems instead of guessing**

> **Architecture is not about drawing boxes.
> It's about making the right trade-offs.**

---

# 🛠️ Technology

### 💻 Software Engineering

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)

### ⚙️ Data Engineering

![Apache Kafka](https://img.shields.io/badge/Kafka-000000?style=for-the-badge\&logo=apachekafka\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge\&logo=apacheairflow\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)

### 🧠 Machine Learning & MLOps

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge\&logo=mlflow\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge\&logo=xgboost\&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-000000?style=for-the-badge\&logo=python\&logoColor=white)

### 🗄️ Databases

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge\&logo=postgresql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)

### ☁️ Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge\&logo=googlecloud\&logoColor=white)

---

# 🎯 Current Focus

### Software Engineering

* Backend architecture
* Distributed systems
* API design
* System reliability
* Software architecture

### Data & ML

* Real-time data processing
* Machine Learning systems
* MLOps
* Feature engineering
* Model evaluation and explainability

### Leadership

* Technical architecture
* Engineering standards
* Technical decision making
* Mentorship
* Delivery and execution
* Building maintainable engineering teams

### Motorsport

* Race simulation
* Telemetry analysis
* Strategy modeling
* Driver and team performance
* Motorsport data infrastructure

---

# 🔬 Open Source & Experimental Engineering

I use side projects as engineering laboratories.

Instead of building isolated demos, I try to turn ideas into **complete systems** with real architecture, APIs, data pipelines, infrastructure, documentation, and reproducible environments.

Some of the areas I explore:

```text
Software Engineering
        │
        ├── Distributed Systems
        ├── APIs
        ├── Data Platforms
        ├── Streaming
        ├── Machine Learning
        ├── MLOps
        └── Simulation
                │
                ▼
        Motorsport Analytics
```

---

# 📊 GitHub

[![GitHub Streak](https://streak-stats.demolab.com?user=palomacdev\&theme=tokyonight\&hide_border=true\&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

![Visitors](https://komarev.com/ghpvc/?username=palomacdev\&style=for-the-badge\&color=E10600\&label=VISITORS)

---

# 📫 Let's Connect

* 💼 **[LinkedIn](https://www.linkedin.com/in/paloma-cordeiro-119750b6)**
* 📧 **[palomacordeiro2009@hotmail.com](mailto:palomacordeiro2009@hotmail.com)**
* 🔬 **[Architecture & Experimental Projects](https://github.com/palomahub-arch)**

---

### 🏎️ Build systems. Solve problems. Measure everything.

**Engineering is the craft. Data is the material. Software is the product.**
