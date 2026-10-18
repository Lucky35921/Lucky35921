
<h1 align="center">Hi 👋, I'm Lakshmana Rao Vallapuneni</h1>

<h3 align="center">
Data Engineer | Azure Data Engineer | Cloud Data Platforms
</h3>

<p align="center">
Building scalable batch and real-time data pipelines across AWS and Azure
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/lakshmanarao-vallapuneni/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:vlakshmanarao05@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Lucky35921">
    <img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **Data Engineer with 4+ years of experience** designing, developing, and optimizing scalable batch and real-time data pipelines across **AWS and Azure**.

My experience spans the complete data engineering lifecycle — from ingestion and ETL/ELT development to distributed processing, orchestration, cloud data warehousing, data quality, performance optimization, and deployment.

- ☁️ Building cloud-native data platforms across AWS and Azure
- ⚡ Developing distributed transformations using PySpark, Spark, and Databricks
- 🔄 Designing ETL/ELT workflows using ADF, AWS Glue, and Airflow
- 🌊 Working with Kafka and Spark Structured Streaming
- 🏗️ Implementing Bronze, Silver, and Gold Medallion Architecture
- ❄️ Designing analytical data models in Snowflake, Redshift, and Synapse
- 📊 Supporting enterprise analytics using Power BI and Qlik
- 🚀 Optimizing Spark jobs and SQL queries
- 🧪 Implementing data quality, reconciliation, and validation
- 🔧 Building CI/CD workflows for data engineering deployments

---

# 🛠️ Technical Stack

### 👨‍💻 Programming & Data Processing

<p>
  <img src="https://skillicons.dev/icons?i=python,mysql,postgres" height="45"/>
</p>

**Python • SQL • PySpark • Spark SQL • Shell Scripting**

### ⚡ Big Data & Streaming

**Apache Spark • PySpark • Databricks • Apache Kafka • Spark Structured Streaming • Hadoop • Delta Lake**

### 🔄 ETL/ELT & Orchestration

**Azure Data Factory • AWS Glue • Apache Airflow • dbt • SSIS**

### ☁️ Cloud Platforms

<p>
  <img src="https://skillicons.dev/icons?i=aws,azure" height="45"/>
</p>

**AWS:** S3, Glue, Redshift, EMR, Lambda, Athena

**Azure:** Data Factory, Databricks, ADLS Gen2, Synapse Analytics, Azure DevOps

### 🏢 Data Warehousing & Architecture

**Snowflake • Amazon Redshift • Azure Synapse • Dimensional Modeling • Star Schema • Medallion Architecture**

### 🔧 DevOps & Engineering

<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker" height="45"/>
</p>

**Git • GitHub • Docker • Azure DevOps • CI/CD • Agile • Scrum**

---

# 🚀 Featured Data Engineering Projects

A collection of hands-on data engineering projects focused on streaming, lakehouse architecture, data quality, CDC, cloud data warehousing, and analytics engineering.

## 1️⃣ Real-Time Customer 360 Lakehouse

### Kafka | PySpark | Delta Lake | Databricks | PostgreSQL

**Project Status:** Local CDC prototype implemented; enterprise integrations in development.

A Customer 360 data engineering platform designed to integrate customer information from operational databases, CRM systems, and event streams into a unified analytical view.

### 🏗️ Target Architecture

**PostgreSQL / APIs → Apache Kafka → Spark Structured Streaming → Delta Lake → Databricks → Power BI**

![Customer 360 Architecture](https://raw.githubusercontent.com/Lucky35921/realtime-customer-360-lakehouse/main/realtime-customer-360-lakehouse/docs/architecture.png)

### Engineering Highlights

- CDC-based customer insert, update, and delete processing
- Event deduplication and late-arriving event protection
- Automated data quality validation and quarantine
- Append-only raw event preservation
- Customer 360 current-state materialization
- Planned Bronze, Silver, and Gold Delta Lake architecture
- Planned Kafka streaming, checkpointing, and incremental Delta MERGE

**Current Implementation:** Python-based CDC processing using synthetic customer events.

**Target Stack:** `Kafka` `PySpark` `Delta Lake` `Databricks` `PostgreSQL` `Airflow`

[![View Project](https://img.shields.io/badge/View_Project-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/realtime-customer-360-lakehouse)

---

## 2️⃣ Streaming Fraud Analytics Platform

### Apache Kafka | Spark Structured Streaming | AWS S3 | Redshift

**Project Status:** Local prototype implemented; cloud streaming integrations planned.

A real-time fraud analytics platform designed to process financial transaction events, detect suspicious activity, and prepare analytical outputs for monitoring and investigation.

### 🏗️ Target Architecture

**Transaction Producers → Kafka → Spark Structured Streaming → Fraud Detection → Amazon S3 → Redshift**

![Fraud Analytics Architecture](https://raw.githubusercontent.com/Lucky35921/streaming-fraud-analytics-platform/main/docs/architecture.png)

### Engineering Highlights

- Synthetic transaction event generation
- Rule-based suspicious transaction detection
- High-value transaction and velocity-based checks
- Duplicate event handling
- Fraud alert generation
- Planned Spark streaming windows and watermarking
- Planned AWS S3 storage and Redshift analytical integration
- Planned pipeline monitoring and checkpoint recovery

**Current Implementation:** Local transaction processing and fraud-rule evaluation.

**Target Stack:** `Kafka` `Spark Structured Streaming` `Python` `AWS S3` `Redshift` `CloudWatch`

[![View Project](https://img.shields.io/badge/View_Project-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/streaming-fraud-analytics-platform)

---

## 3️⃣ Enterprise Snowflake Analytics Platform

### Snowflake | dbt | Apache Airflow | SQL | Dimensional Modeling

**Project Status:** Local SQL analytics prototype implemented; Snowflake and dbt deployment planned.

An enterprise-style ELT analytics platform designed to centralize retail business data from multiple sources, implement modular transformations, and deliver governed analytical data marts.

### 🏗️ Target Architecture

**Retail Data Sources → Airflow → Snowflake → dbt → Dimensional Data Marts → Business Intelligence**

![Snowflake Analytics Architecture](https://raw.githubusercontent.com/Lucky35921/enterprise-snowflake-analytics-platform/main/docs/architecture.png)

### Engineering Highlights

- Retail customer and order data ingestion
- SQL-based data cleaning and transformation
- Staging and analytical data modeling
- Customer and product dimensions
- Sales and revenue fact tables
- Data validation and consistency checks
- Planned dbt incremental models and automated testing
- Planned SCD Type 2 history and data lineage
- Planned Airflow orchestration and Snowflake optimization

**Current Implementation:** Local SQL transformations using synthetic retail datasets.

**Target Stack:** `Snowflake` `dbt` `SQL` `Airflow` `Dimensional Modeling` `Power BI`

[![View Project](https://img.shields.io/badge/View_Project-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/enterprise-snowflake-analytics-platform)

---

# 💼 Professional Experience

## 🔹 Data Engineer — Deloitte

**July 2025 – Present | Grand Rapids, Michigan**

- Engineered scalable ETL/ELT pipelines using Python, SQL, PySpark, and AWS.
- Processed millions of records daily for enterprise analytics and reporting.
- Built dependency-aware Apache Airflow DAGs with retries, alerts, and SLA monitoring.
- Optimized SQL queries using execution plans, indexing, and join optimization.
- Reduced a critical reporting query from **120 seconds to 3 seconds**.
- Developed automated data quality and validation frameworks.
- Implemented secure data handling with access controls, masking, and auditing.

---

## 🔹 Azure Data Engineer — Tech Mahindra

**April 2022 – July 2024 | India**

- Migrated enterprise ETL workloads from legacy on-premises systems to Azure.
- Built pipelines using Azure Data Factory, Databricks, ADLS Gen2, and Spark.
- Implemented Bronze, Silver, and Gold Medallion Architecture.
- Developed large-scale PySpark and Spark SQL transformations.
- Optimized Spark processing using partitioning, caching, and broadcast joins.
- Diagnosed pipeline failures and data discrepancies.
- Established Azure DevOps CI/CD workflows across development, UAT, and production.

---

## 🔹 Associate Data Engineer — HCLTech

**May 2021 – March 2022 | India**

- Developed data ingestion frameworks using Kafka, REST APIs, and CDC concepts.
- Built ETL workflows using Azure Data Factory, Databricks, and PySpark.
- Designed analytical data models using Snowflake and dimensional modeling.
- Implemented source-to-target reconciliation and data validation.
- Supported enterprise data processing and reporting workloads.

---

# 🎯 Engineering Expertise

| Area | Technologies |
|------|-------------|
| Programming | Python, SQL, PySpark, Spark SQL |
| Big Data | Spark, Databricks, Hadoop |
| Streaming | Kafka, Spark Structured Streaming |
| Azure | ADF, ADLS Gen2, Databricks, Synapse |
| AWS | S3, Glue, Redshift, EMR, Lambda |
| Warehousing | Snowflake, Redshift, Synapse |
| Orchestration | Airflow, ADF |
| Transformation | PySpark, Spark SQL, dbt |
| Architecture | Medallion, CDC, Dimensional Modeling |
| DevOps | Git, GitHub, Docker, Azure DevOps |
| BI | Power BI, Qlik, Tableau |

---

# 📚 Currently Exploring

- Advanced Apache Kafka
- dbt and Analytics Engineering
- Spark performance optimization
- Data pipeline observability
- Cloud data architecture
- Distributed systems and data engineering design

---

# 🎓 Education

### Master of Science — Data Science & Analytics

**Grand Valley State University**  
Grand Rapids, Michigan  
**April 2026**

---

# 🏆 Certifications

- Microsoft Certified: Azure Data Engineer Associate
- AWS Certified Machine Learning

---

# 📊 GitHub Activity

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Lucky35921&show_icons=true&hide_border=true"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Lucky35921&hide_border=true"/>
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucky35921&layout=compact&hide_border=true"/>
</p>

---

# 🤝 Let's Connect

I'm interested in solving challenging problems in **Data Engineering, Cloud Data Platforms, Big Data, Streaming, and Analytics Engineering**.

<p align="center">
  <a href="https://www.linkedin.com/in/lakshmanarao-vallapuneni/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:vlakshmanarao05@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Lucky35921">
    <img src="https://img.shields.io/badge/GitHub-Lucky35921-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <b>Data Engineering • Cloud • Big Data • Streaming • Analytics Engineering</b>
</p>
