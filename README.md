
<div align="center">

# LAKSHMANA RAO VALLAPUNENI

### DATA ENGINEER · CLOUD DATA PLATFORMS · DISTRIBUTED SYSTEMS

**Engineering scalable data platforms, reliable pipelines, and analytics-ready systems.**

<br/>

[![Portfolio](https://img.shields.io/badge/Explore-My_Projects-2563EB?style=for-the-badge&logo=github&logoColor=white)](#featured-projects)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmanarao-vallapuneni/)
[![Email](https://img.shields.io/badge/Email-Get_in_Touch-374151?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vlakshmanarao05@gmail.com)

<br/>

`AWS` · `AZURE` · `DATABRICKS` · `PYSPARK` · `KAFKA` · `SNOWFLAKE` · `AIRFLOW`

---

[**About**](#about-me) &nbsp; • &nbsp;
[**Tech Stack**](#technology-stack) &nbsp; • &nbsp;
[**Projects**](#featured-projects) &nbsp; • &nbsp;
[**Experience**](#professional-experience) &nbsp; • &nbsp;
[**Contact**](#connect)

</div>

<br/>

<a id="about-me"></a>

## 👨‍💻 About Me

I'm a **Data Engineer** focused on designing and optimizing cloud-native data platforms, distributed processing pipelines, and enterprise analytics solutions.

My work spans **batch and streaming ETL/ELT, data lakehouse architecture, SQL and Spark performance optimization, data quality engineering, cloud warehousing, and workflow orchestration**.

I approach data engineering with an emphasis on:

- **Scalability** — Efficient distributed processing and incremental data pipelines.
- **Reliability** — Idempotency, validation, failure recovery, and auditability.
- **Performance** — Optimized SQL execution, Spark transformations, and data modeling.
- **Maintainability** — Reusable pipeline components, testing, and CI/CD.
- **Business Impact** — Trusted datasets that support reporting and decision-making.

> **Engineering philosophy:** A successful data platform is not just one that processes data — it is one that remains reliable, observable, and maintainable as data volumes and business requirements evolve.

<br/>

<a id="technology-stack"></a>

## ⚙️ Technology Stack

<div align="center">

### Languages & Distributed Processing

<img src="https://skillicons.dev/icons?i=python,postgres,mysql" height="48" alt="Programming technologies"/>

<br/><br/>

![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Spark SQL](https://img.shields.io/badge/Spark_SQL-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

### Cloud & Data Platforms

<img src="https://skillicons.dev/icons?i=aws,azure" height="48" alt="Cloud platforms"/>

<br/><br/>

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Redshift](https://img.shields.io/badge/Amazon_Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square)

### Streaming & Orchestration

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![ADF](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat-square)

### Development & DevOps

<img src="https://skillicons.dev/icons?i=git,github,docker,vscode" height="48" alt="Development tools"/>

</div>

<br/>

---

<a id="featured-projects"></a>

## 🚀 Featured Projects

**Selected data engineering projects exploring enterprise architecture, real-time streaming, CDC, cloud data warehousing, and analytical modeling.**

### 01 / Real-Time Customer 360 Lakehouse

**CUSTOMER DATA PLATFORM · CDC · LAKEHOUSE ARCHITECTURE**

<div align="center">

<img src="https://raw.githubusercontent.com/Lucky35921/realtime-customer-360-lakehouse/main/realtime-customer-360-lakehouse/docs/architecture.png" alt="Customer 360 Lakehouse Architecture" width="95%"/>

</div>

<br/>

A Customer 360 lakehouse project designed to consolidate customer data from operational systems into a unified analytical view.

**Architecture**

`PostgreSQL / APIs → Kafka → Spark Streaming → Delta Lake → Databricks → Analytics`

**Engineering Highlights**

- Implemented local CDC processing for customer insert, update, and delete events.
- Built deterministic event ordering and deduplication logic.
- Added late-arriving event protection and invalid-record quarantine.
- Preserved raw customer events for replay and auditing.
- Designed a future Bronze, Silver, and Gold Delta Lake architecture.
- Planned distributed streaming, incremental MERGE, and orchestration.

**Tech:** `Python` `PostgreSQL` `Kafka` `PySpark` `Delta Lake` `Databricks`

**Status:** Local CDC prototype implemented; cloud streaming integration planned.

[![Source Code](https://img.shields.io/badge/View_Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/realtime-customer-360-lakehouse)

<br/>

---

### 02 / Streaming Fraud Analytics Platform

**FINANCIAL DATA ENGINEERING · STREAMING · EVENT PROCESSING**

<div align="center">

<img src="https://raw.githubusercontent.com/Lucky35921/Streaming-Fraud-Analytics-Platform/main/streaming-fraud-analytics-platform/docs/architecture.svg" alt="Streaming Fraud Analytics Architecture" width="95%"/>

</div>

<br/>

An event-driven fraud analytics project designed to process financial transaction streams, identify suspicious activity, and produce fraud monitoring outputs.

**Architecture**

`Transaction Producers → Kafka → Spark Streaming → Fraud Detection → S3 → Redshift`

**Engineering Highlights**

- Developed local transaction event processing and fraud detection rules.
- Applied high-value transaction and transaction velocity checks.
- Included duplicate-event handling and fraud alert generation.
- Designed streaming windows and watermarking for future implementation.
- Planned AWS S3 storage, Redshift analytics, and pipeline monitoring.

**Tech:** `Python` `Kafka` `Spark Structured Streaming` `AWS S3` `Redshift`

**Status:** Local fraud detection prototype implemented; distributed streaming and AWS deployment planned.

[![Source Code](https://img.shields.io/badge/View_Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/Streaming-Fraud-Analytics-Platform)

<br/>

---

### 03 / Enterprise Snowflake Analytics Platform

**CLOUD DATA WAREHOUSING · ELT · ANALYTICS ENGINEERING**

<div align="center">

<img src="https://raw.githubusercontent.com/Lucky35921/enterprise-snowflake-analytics-platform/main/enterprise-snowflake-analytics-platform-with-architecture/docs/architecture.png" alt="Enterprise Snowflake Analytics Architecture" width="95%"/>

</div>

<br/>

An enterprise-style analytics engineering project designed to standardize retail data ingestion, SQL transformations, and dimensional data modeling.

**Architecture**

`Retail Sources → Airflow → Snowflake → dbt → Analytics Marts → BI`

**Engineering Highlights**

- Developed local SQL-based retail data transformations.
- Designed staging models and curated analytical datasets.
- Modeled customer and product dimensions with sales fact tables.
- Applied data validation and consistency checks.
- Planned dbt incremental models, SCD Type 2 history, and automated testing.
- Designed Airflow orchestration and Snowflake analytical integration.

**Tech:** `Snowflake` `dbt` `SQL` `Airflow` `Dimensional Modeling`

**Status:** Local SQL prototype implemented; Snowflake, dbt, and Airflow integrations planned.

[![Source Code](https://img.shields.io/badge/View_Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921/enterprise-snowflake-analytics-platform)

<br/>

---

<a id="professional-experience"></a>

## 💼 Professional Experience

### Data Engineer — Deloitte

**July 2025 – Present | Grand Rapids, Michigan**

- Developed and optimized ETL/ELT pipelines using Python, SQL, PySpark, and AWS.
- Built enterprise reporting data workflows and automated validation frameworks.
- Implemented Airflow orchestration with retries, dependency management, and alerts.
- Tuned SQL queries through execution-plan analysis and indexing.
- Improved a critical reporting query from **120 seconds to 3 seconds**.
- Supported data quality, reconciliation, and secure data processing.

`AWS` `Python` `PySpark` `SQL` `Airflow` `Data Quality`

---

### Azure Data Engineer — Tech Mahindra

**April 2022 – July 2024 | India**

- Developed Azure ETL pipelines using ADF, Databricks, ADLS Gen2, and Spark.
- Supported migration from legacy data processing systems to cloud platforms.
- Implemented Bronze, Silver, and Gold Medallion Architecture.
- Optimized PySpark workloads using partitioning, caching, and broadcast joins.
- Supported Azure DevOps CI/CD workflows and pipeline troubleshooting.

`Azure` `ADF` `Databricks` `ADLS Gen2` `PySpark` `CI/CD`

---

### Associate Data Engineer — HCLTech

**May 2021 – March 2022 | India**

- Developed enterprise data ingestion and transformation workflows.
- Worked with REST APIs, Kafka, and CDC processing concepts.
- Supported ETL pipelines using ADF, Databricks, and PySpark.
- Designed analytical models using Snowflake and dimensional modeling.
- Implemented data validation and reconciliation processes.

`ETL` `Kafka` `Snowflake` `SQL` `Data Integration`

<br/>

---

## 🏗️ Engineering Principles

| Principle | Focus |
|---|---|
| **Reliable Pipelines** | Retries, recovery, validation, and reconciliation |
| **Scalable Processing** | Distributed computing, partitioning, incremental loads |
| **Data Correctness** | Deduplication, idempotency, CDC, late-event handling |
| **Observability** | Audit logs, metrics, monitoring, and alerting |
| **Performance** | Spark tuning, SQL optimization, data modeling |
| **Maintainability** | Reusable components, automated tests, CI/CD |
| **Governance** | Lineage, access controls, historical traceability |

---

## 🎓 Education

**Master of Science in Data Science & Analytics**

Grand Valley State University — Grand Rapids, Michigan

April 2026

---

## 🏆 Certifications

- Microsoft Certified: Azure Data Engineer Associate
- AWS Certified Machine Learning

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Lucky35921&show_icons=true&hide_border=true" width="48%" alt="GitHub stats"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucky35921&layout=compact&hide_border=true" width="48%" alt="Top languages"/>

</div>

<br/>

---

<a id="connect"></a>

<div align="center">

## Let's Connect

**Open to conversations about Data Engineering, Distributed Systems, Cloud Data Platforms, and Analytics Engineering.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmanarao-vallapuneni/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vlakshmanarao05@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/Lucky35921)

<br/>

---

**DATA ENGINEERING · CLOUD ARCHITECTURE · STREAMING · ANALYTICS**

*Engineering reliable data systems that turn raw information into trusted business insights.*

</div>
