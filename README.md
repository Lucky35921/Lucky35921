
<div align="center">

# Lakshmana Rao Vallapuneni

### Data Engineer | AWS & Azure | Distributed Data Systems | Lakehouse & Streaming Architecture

**Building reliable, scalable, and production-oriented data platforms**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmanarao-vallapuneni/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vlakshmanarao05@gmail.com)

</div>

---

## Professional Overview

Data Engineer with experience designing, developing, and optimizing enterprise data pipelines across **AWS, Azure, and distributed processing environments**.

Specializing in **ETL/ELT architecture, PySpark optimization, cloud data platforms, real-time streaming, data quality engineering, and analytical data modeling**.

My engineering approach focuses on building systems that are not only scalable but also **reliable, observable, maintainable, and cost-efficient**.

### Areas of Engineering Expertise

- **Data Platform Engineering:** Batch and streaming pipelines, reusable ETL frameworks, lakehouse architecture, and cloud data integration.
- **Distributed Processing:** Apache Spark, PySpark, partitioning strategies, join optimization, caching, and performance tuning.
- **Real-Time Data Systems:** Apache Kafka, Spark Structured Streaming, CDC, event-time processing, and incremental ingestion.
- **Data Reliability:** Automated validation, reconciliation, deduplication, quarantine handling, audit logging, and failure recovery.
- **Cloud & Warehousing:** AWS, Azure, Databricks, Snowflake, Redshift, and Synapse Analytics.
- **Analytics Engineering:** Dimensional modeling, star schemas, incremental transformations, dbt, and analytics-ready data marts.
- **Orchestration & DevOps:** Apache Airflow, Azure Data Factory, Docker, Git, and CI/CD.

---

# Technology Ecosystem

### Languages & Processing

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

### Cloud & Data Platforms

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

### Streaming, Orchestration & Transformation

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

| Engineering Domain | Technologies |
|---|---|
| Programming | Python, SQL, PySpark, Spark SQL |
| Distributed Computing | Apache Spark, Databricks, Hadoop |
| Streaming & CDC | Apache Kafka, Spark Structured Streaming, CDC |
| AWS | S3, Glue, Redshift, EMR, Athena, Lambda |
| Azure | Data Factory, ADLS Gen2, Databricks, Synapse |
| Warehousing | Snowflake, Redshift, Azure Synapse |
| Orchestration | Apache Airflow, Azure Data Factory |
| Transformation | dbt, PySpark, Spark SQL |
| Architecture | Medallion, Data Lakehouse, Dimensional Modeling |
| Reliability | Data Quality, Audit Logging, Reconciliation, Monitoring |
| DevOps | Git, GitHub, Docker, Azure DevOps, CI/CD |
| Analytics | Power BI, Tableau, Qlik |

---

# Featured Data Engineering Projects

**Architecture-focused engineering projects demonstrating CDC, streaming analytics, cloud warehousing, and data platform design.**

The projects currently include local prototypes and planned enterprise integrations. Each repository documents its implemented features and target architecture.

## 01 — Real-Time Customer 360 Lakehouse

**Domain:** Customer Data Platform | CDC | Lakehouse Engineering

**Technology:** Kafka · PySpark · Delta Lake · Databricks · PostgreSQL

![Customer 360 Architecture](https://raw.githubusercontent.com/Lucky35921/realtime-customer-360-lakehouse/main/realtime-customer-360-lakehouse/docs/architecture.png)

### Engineering Problem

Customer information distributed across multiple operational systems can create inconsistent customer records, duplicate events, stale attributes, and unreliable analytical outputs.

### Solution Architecture

Designed a Customer 360 lakehouse architecture to unify operational customer data through CDC ingestion, distributed transformations, and curated analytical datasets.

**Target Data Flow:**

`PostgreSQL / APIs → Kafka → Spark Structured Streaming → Delta Lake → Databricks → Analytics`

### Engineering Capabilities

- CDC event ingestion and insert/update/delete processing.
- Deterministic event ordering and duplicate-event handling.
- Late-arriving event protection.
- Data quality validation and rejected-record quarantine.
- Append-only raw event retention for replay and auditing.
- Customer 360 current-state materialization.
- Planned Delta Lake incremental MERGE and Medallion Architecture.
- Planned checkpointing, orchestration, and observability.

**Implementation Status:** Local Python CDC prototype available. Distributed streaming and cloud deployment are planned.

[![Explore Repository](https://img.shields.io/badge/Explore_Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/realtime-customer-360-lakehouse)

---

## 02 — Streaming Fraud Analytics Platform

**Domain:** Financial Data Engineering | Event-Driven Architecture | Streaming Analytics

**Technology:** Kafka · Spark Structured Streaming · AWS S3 · Amazon Redshift

![Streaming Fraud Architecture](https://raw.githubusercontent.com/Lucky35921/streaming-fraud-analytics-platform/main/docs/architecture.png)

### Engineering Problem

Financial transaction streams require timely processing, consistent event handling, and detection of suspicious behavior while maintaining reliable downstream analytics.

### Solution Architecture

Designed an event-driven fraud analytics platform to ingest transaction events, apply configurable fraud detection rules, and generate analytical outputs for investigation and monitoring.

**Target Data Flow:**

`Transaction Producers → Kafka → Spark Structured Streaming → Fraud Rules → S3 → Redshift`

### Engineering Capabilities

- Synthetic financial transaction event generation.
- High-value transaction detection.
- Transaction velocity analysis.
- Duplicate-event handling.
- Rule-based anomaly classification.
- Fraud alert generation.
- Planned event-time windows and watermarking.
- Planned Spark checkpointing and recovery.
- Planned AWS-based storage, monitoring, and analytics.

**Implementation Status:** Local fraud-rule prototype available. Kafka, Spark streaming, and AWS integrations are planned.

[![Explore Repository](https://img.shields.io/badge/Explore_Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/streaming-fraud-analytics-platform)

---

## 03 — Enterprise Snowflake Analytics Platform

**Domain:** Cloud Data Warehousing | ELT | Analytics Engineering

**Technology:** Snowflake · dbt · Apache Airflow · SQL · Dimensional Modeling

![Snowflake Analytics Architecture](https://raw.githubusercontent.com/Lucky35921/enterprise-snowflake-analytics-platform/main/docs/architecture.png)

### Engineering Problem

Fragmented retail data and inconsistent transformation logic make it difficult to deliver reliable reporting, historical analysis, and reusable analytical datasets.

### Solution Architecture

Designed an enterprise ELT analytics architecture to standardize retail data ingestion, modularize SQL transformations, and deliver dimensional data marts for business intelligence.

**Target Data Flow:**

`Retail Sources → Airflow → Snowflake → dbt → Analytics Marts → BI`

### Engineering Capabilities

- Retail data ingestion and SQL-based transformations.
- Staging and curated analytical models.
- Customer and product dimensions.
- Sales and revenue fact tables.
- Data consistency and validation checks.
- Planned incremental dbt models.
- Planned SCD Type 2 historical tracking.
- Planned automated dbt testing and documentation.
- Planned Airflow orchestration and Snowflake optimization.

**Implementation Status:** Local SQL analytics prototype available. Snowflake, dbt, and Airflow integrations are planned.

[![Explore Repository](https://img.shields.io/badge/Explore_Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/enterprise-snowflake-analytics-platform)

---

# Professional Experience

## Data Engineer | Deloitte

**July 2025 – Present | Grand Rapids, Michigan**

- Engineered scalable ETL/ELT pipelines using Python, SQL, PySpark, and AWS.
- Developed data processing workflows supporting enterprise reporting and analytics.
- Built dependency-aware Airflow DAGs with retry mechanisms, alerts, and SLA monitoring.
- Optimized SQL workloads through execution-plan analysis, indexing, and join optimization.
- Improved a critical reporting query from **120 seconds to 3 seconds**.
- Implemented data quality checks, reconciliation logic, and automated validation.
- Supported secure handling of enterprise data using access controls and auditing.

### Engineering Focus

`ETL/ELT` `PySpark` `AWS` `SQL Optimization` `Airflow` `Data Reliability`

---

## Azure Data Engineer | Tech Mahindra

**April 2022 – July 2024 | India**

- Developed Azure-based ETL pipelines using Data Factory, Databricks, ADLS Gen2, and Spark.
- Supported migration of legacy ETL workloads to cloud data platforms.
- Implemented Medallion Architecture with Bronze, Silver, and Gold processing layers.
- Built PySpark and Spark SQL transformations for enterprise datasets.
- Optimized distributed workloads through partitioning, caching, and broadcast joins.
- Troubleshot pipeline failures and source-to-target data discrepancies.
- Supported CI/CD deployment workflows using Azure DevOps.

### Engineering Focus

`Azure` `ADF` `Databricks` `PySpark` `Medallion Architecture` `CI/CD`

---

## Associate Data Engineer | HCLTech

**May 2021 – March 2022 | India**

- Developed ingestion and transformation workflows for enterprise data integration.
- Worked with Kafka, REST APIs, and CDC-based data processing concepts.
- Supported ETL development using Azure Data Factory, Databricks, and PySpark.
- Designed analytical models using Snowflake and dimensional modeling techniques.
- Implemented source-to-target reconciliation and data validation.

### Engineering Focus

`Data Integration` `Kafka` `ETL` `Snowflake` `SQL` `Data Quality`

---

# Data Engineering Design Principles

| Principle | Engineering Approach |
|---|---|
| Reliability | Retries, validation, reconciliation, and failure handling |
| Scalability | Partitioning, distributed processing, incremental workloads |
| Data Quality | Rule-based checks, quarantine, and schema validation |
| Idempotency | Deduplication, deterministic merges, replay-safe processing |
| Observability | Audit logs, execution metrics, and pipeline monitoring |
| Maintainability | Modular transformations, reusable frameworks, testing |
| Performance | Spark optimization, query tuning, efficient data modeling |
| Governance | Data lineage, access controls, and historical traceability |

---

# Education

### Master of Science in Data Science & Analytics

**Grand Valley State University**  
Grand Rapids, Michigan | April 2026

---

# Certifications

- Microsoft Certified: Azure Data Engineer Associate
- AWS Certified Machine Learning

---

# GitHub Engineering Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Lucky35921&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Lucky35921&layout=compact&hide_border=true)

</div>

---

# Connect

Interested in opportunities involving:

**Data Engineering • Cloud Data Platforms • Distributed Processing • Streaming Systems • Analytics Engineering**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmanarao-vallapuneni/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vlakshmanarao05@gmail.com)

---

<div align="center">

**Engineering data platforms for reliability, scalability, and business impact.**

</div>
