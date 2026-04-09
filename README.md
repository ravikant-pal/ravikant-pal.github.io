<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Ravikant%20Pal&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Senior%20Data%20Engineer&descAlignY=58&descColor=a8d8ea" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ravikant--pal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ravikant-pal)
[![GitHub](https://img.shields.io/badge/GitHub-ravikant--pal-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ravikant-pal)
[![Email](https://img.shields.io/badge/Email-iamravikantpal%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iamravikantpal@gmail.com)
[![Location](https://img.shields.io/badge/Based_In-Bangalore%2C_India-FF6B35?style=for-the-badge&logo=googlemaps&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Immediate_Joiner-00C851?style=for-the-badge)]()
[![Relocate](https://img.shields.io/badge/Open_To-Netherlands_%7C_Europe-FF9900?style=for-the-badge)]()

<br/>

> **6+ years building TB-scale pipelines, real-time CDC systems, and cloud-native analytics platforms.**
> Founder of a live SaaS product with 200+ paying customers. Immediate joiner. Relocating to the Netherlands.

</div>

---

## Who I Am

I am a Senior Data Engineer who builds data systems that survive production at scale.

My work spans real-time CDC pipelines with sub-second latency, TB-scale PySpark ETL, analytics infrastructure on Snowflake and PostgreSQL, and distributed data architectures with no central database. I have shipped these systems across AdTech, HR tech, fintech, and SaaS domains.

I also founded a SaaS platform that reached 200+ paying customers built on a local-first distributed data architecture designed entirely from scratch, no team, no funding.

I am currently expanding into AWS Glue, dbt, and Databricks Delta Lake to round out the modern lakehouse stack.

---

## Tech Stack

### Core (Production Experience)

| Domain | Technologies |
|--------|-------------|
| **Languages** | Python · PySpark · SQL · Java 8-21 · Kotlin |
| **Batch Processing** | Apache Spark · PySpark · Spark SQL · Spark Streaming · Distributed ETL |
| **Stream Processing** | Apache Kafka · Kafka Streams · Kafka Connect · Event-Driven Architecture |
| **CDC Pipelines** | Debezium · Change Data Capture · Log-based replication · Kafka Connect |
| **Data Warehousing** | Snowflake · PostgreSQL · Cassandra · MySQL · Redis · MongoDB |
| **Search and Analytics** | Elasticsearch · ELK Stack |
| **AWS (Data)** | S3 · MSK (Managed Kafka) · Redshift · Athena · Kinesis · Lambda · EMR · CloudWatch · IAM · EKS · EC2 |
| **Containers and Infra** | Docker · Kubernetes · Helm · Terraform · ArgoCD · Jenkins · CI/CD |
| **Observability** | Datadog · Prometheus · Grafana · ELK Stack · Automated Alerting · Schema Validation |
| **Data Modeling** | Dimensional Modeling · Partitioning Strategies · Data Vault concepts · ETL/ELT patterns |

### Expanding (Active Learning)

| Domain | Technologies |
|--------|-------------|
| **AWS Managed ETL** | AWS Glue · Glue Data Catalog · Glue Crawlers · Glue Studio |
| **Lakehouse** | Databricks · Delta Lake · Unity Catalog · Medallion Architecture |
| **Transformation** | dbt · SQL-first modeling · data lineage · incremental models |
| **GCP (Data)** | BigQuery · Dataflow (Apache Beam) · Pub/Sub · Dataproc · Cloud Composer · Cloud Storage · Looker Studio |

---

## Experience

### MML — Library Management SaaS (Self-Founded)
**Founder and Data Architect** | Sep 2025 — Present | Bangalore

Built a production SaaS platform from zero, solo. Designed every layer of the data architecture from client-side storage to sync pipelines to multi-tenant isolation.

- Designed a **local-first distributed data architecture** using IndexedDB as the primary storage layer and Google Drive as the cloud sync medium, eliminating central database infrastructure entirely
- Engineered **multi-device data synchronization** across up to 5 devices per account with a custom conflict resolution strategy inspired by CRDT merge semantics
- Built **ETL migration pipelines** from centralized MongoDB infrastructure to decentralized client-side storage, achieving near-zero infrastructure cost while maintaining full data reliability across all active tenants
- Implemented **multi-tenant data isolation** using database sharding techniques, ensuring complete separation of data operations across 500+ tenant accounts
- Built **cron-based automation pipelines** for notification delivery, coupon campaign processing, and communication workflows, cutting all manual operations to zero
- Designed **role-based data access control** covering Admin, Manager, Sales, and Partner roles with scoped read/write permissions enforced at the data layer
- Established **data observability and reliability systems** to monitor sync health, detect conflicts, and surface anomalies across all active tenants in real time
- Platform live at [managemylibrary.com](https://managemylibrary.com) with **200+ paying customers and 300+ free users**

---

### Employ Inc
**Senior Data Engineer** | Oct 2024 — Mar 2026 | Bangalore

Built the data backbone for an enterprise HR tech platform operating across multiple ATS products at scale.

- Designed and maintained **distributed Spark ETL workflows** on AWS EKS ingesting candidate applications, screening results, and onboarding metrics from multiple ATS products at TB scale
- Built **real-time CDC pipelines using Debezium and Kafka** to synchronize data from multiple PostgreSQL operational databases into analytics systems with sub-second latency
- Delivered **ENT Data Pipelines**: a streaming aggregation platform pulling event streams from multiple microservices into centralized Snowflake analytics storage
- Implemented **automated data quality validation** with schema enforcement, completeness checks, null-rate monitoring, and anomaly alerting before issues propagated to downstream HR analytics
- Reduced analytical query latency by **40%** through Snowflake clustering key optimization and PostgreSQL index tuning on high-cardinality workloads
- Delivered **data models for talent acquisition KPIs**: time-to-hire, source effectiveness, funnel conversion, and offer acceptance rates, partnering directly with Product and Analytics teams
- Managed **Kubernetes-deployed pipeline infrastructure** using Helm charts and ArgoCD for declarative deployment and rollback of Spark and Kafka workloads
- Integrated **Datadog and Prometheus monitoring** to track pipeline SLAs, Kafka consumer lag, and Snowflake query performance across all production jobs

---

### Times Internet
**Data Engineer** | Sep 2023 — Oct 2024 | Noida

Built the analytics data infrastructure for one of India's largest digital media and AdTech companies.

- Designed and implemented **PySpark batch pipelines** processing TB-scale clickstream, campaign impression, and revenue data for the AdTech analytics platform on daily and hourly schedules
- Built **real-time Kafka streaming pipelines** for near real-time ad event ingestion and processing, delivering campaign performance metrics with sub-minute freshness
- Designed and optimized **PostgreSQL and Cassandra storage layers** using partitioning strategies and materialized views to reduce query latency by 35% on high-volume analytical workloads
- Built **data validation and observability pipelines** that automated anomaly detection across ingestion jobs, reducing silent data failures by 60%
- Designed **schema evolution strategies for Kafka topics** to handle ad format changes without breaking downstream consumer pipelines
- Modeled **campaign attribution and conversion data** to support advertiser reporting dashboards consumed by sales and account management teams
- Collaborated with backend engineers to define **Kafka topic contracts and event schemas**, ensuring clean data contracts between upstream producers and downstream pipelines

**Software Engineer (Data Infrastructure)** | Sep 2021 — Sep 2023 | Noida

Contributed to the data infrastructure and event platform powering the AdTech analytics ecosystem before transitioning to the dedicated Data Engineering role.

- Designed the **event ingestion layer** using Spring Boot and Kafka that served as the upstream data source for all downstream analytics pipelines, processing millions of ad events per day
- Built the **data layer for Colombia Online** (a full-scale AdTech platform): PostgreSQL schema for campaign metadata, auction events, and revenue attribution consumed directly by Spark analytics jobs
- Implemented a **Centralized Logging System using ELK Stack and Kafka**, aggregating structured logs from distributed microservices and improving root cause analysis efficiency by 40%
- Led migration from **monolithic data storage to a microservices-oriented data model**, enabling independent schema evolution per domain and reducing cross-service data coupling
- Built **Kafka-backed event pipelines** for transaction, meta, and notification services that formed the event backbone ingested by data engineering batch and streaming jobs
- Integrated **AI-powered Creatives (AdGPT)** and a live Reporting Dashboard into the data platform, contributing to **$20M in incremental advertising revenue within 3 months**
- Developed an in-house workflow and ticketing data system, reducing manual data operations by **95%, from 20 hours to 5 minutes per cycle**

---

### Kane Solutions
**Software Engineer** | Jul 2020 — Sep 2021 | Noida

- Built **backend data APIs and workflow engines** for financial systems using Java and PostgreSQL, supporting multi-approval policy onboarding flows with full audit trails
- Designed **relational data models** for policy, customer, and transaction domains with normalized schemas optimized for transactional workloads
- Implemented **audit and validation frameworks** to enforce data integrity constraints across all financial approval workflows
- Built **multi-step state machine persistence** using PostgreSQL to track policy lifecycle events with complete event history for compliance reporting
- Enhanced system scalability by **redesigning the policy flow engine** to handle concurrent approval requests without race conditions or data inconsistencies
- Wrote **comprehensive unit and integration test coverage** for all data access and transformation logic across payment and transaction flows

---

### MountBlue Technologies
**Software Development Engineer** | Jul 2019 — Jun 2020 | Bangalore

- Built **fintech data processing modules** using Spring MVC and PostgreSQL, handling payment transaction records and ledger reconciliation logic
- Designed **scalable relational data models** for transaction, account, and audit domains with appropriate normalization and indexing strategies
- Built **reusable data transformation components** for ETL-style processing of financial records between upstream systems and reporting tables
- Maintained **high unit test coverage** across all data access layers, ensuring correctness of transformation logic and edge case handling for financial data
- Optimized **SQL queries and stored procedures** for performance on high-frequency transaction tables with large historical data volumes
- Contributed to **API design for financial data services**, defining clean contracts between the data layer and application layer

---

## Projects

### Earthquake ETL Pipeline and Live Heatmap

A production-style batch ETL pipeline that ingests live global earthquake data from the USGS API every hour, stores it in a partitioned PostgreSQL database, and serves an interactive heatmap — all running locally with a single command.

```bash
docker-compose up
```

**What it does:**

- Ingests earthquake events from the USGS GeoJSON Feed on an hourly schedule using a Python scheduler
- Parses, validates, and transforms raw API responses into a clean schema before loading into PostgreSQL
- Stores data in a **time-partitioned PostgreSQL table** partitioned by event date for efficient range queries
- Deduplicates ingestion runs using event ID to ensure idempotent pipeline execution on every run
- Serves an interactive Dash/Plotly heatmap at `http://localhost:8050`

**Live map preview:**

Once running, open `http://localhost:8050`. The map renders all seismic events from the past 30 days, magnitude-weighted, with a toggle between heatmap layer and individual point layer. The stats panel refreshes automatically every 5 minutes showing event counts by magnitude range, most active region, and average depth.

**Stack:** Python · PostgreSQL · Docker · PySpark · Plotly Dash · USGS API · Partitioned tables · Idempotent ingestion

[![View on GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ravikant-pal)

---

### MML Data Architecture — Local-First Distributed Sync

The data engineering problem underneath a SaaS product: how do you synchronize structured data across 5 devices per tenant, for 500+ tenants, with no central database and zero infrastructure cost?

**What was designed and built:**

- A **client-side storage layer** using IndexedDB as the primary write store, replacing a centralized MongoDB cluster
- A **custom sync engine** that detects local changes, serializes deltas, and pushes them to Google Drive as the cloud storage medium
- A **conflict resolution algorithm** that merges concurrent writes from multiple devices using timestamp-priority with field-level granularity
- **ETL migration pipelines** that moved all existing tenant data from MongoDB to the new decentralized architecture with zero downtime and zero data loss
- A **multi-tenant isolation model** using sharding patterns to ensure one tenant's data operations never touch another's storage space

**Why it is a data engineering problem:** The constraints (no server, no central DB, multi-device writes, eventual consistency) required the same thinking as designing a distributed pipeline with exactly-once semantics and partition isolation.

**Stack:** JavaScript · IndexedDB · Google Drive API · Custom conflict resolution · Sharding patterns · ETL migration scripts

[![Live Product](https://img.shields.io/badge/Live_at-managemylibrary.com-00C851?style=for-the-badge)](https://managemylibrary.com)

---

## What I Am Learning Right Now

| Tool | Current State | Why |
|------|--------------|-----|
| **AWS Glue** | Building ETL jobs, exploring Glue Data Catalog and Crawlers | AWS-native managed ETL is standard in Dutch cloud-first DE stacks |
| **dbt** | SQL-first modeling, incremental models, lineage graphs | Snowflake-heavy teams in the Netherlands use dbt as the transformation standard |
| **Databricks / Delta Lake** | Lakehouse architecture, Delta table internals, medallion patterns | Increasingly required alongside Spark in Amsterdam-based DE roles |

---

## Education

**B.Tech — Computer Science and Engineering**
Dr. A P J Abdul Kalam Technical University | 2015 — 2019 | Uttar Pradesh, India

---

## Languages

English — Professional Proficiency, 
Hindi — Native, 
Dutch — Beginner (A1, in progress)

---

<div align="center">

### Open to Relocation: Netherlands (Amsterdam preferred) and broader Europe

**EU work authorization sponsorship may be required. Immediate joiner. Available from day one.**

If you are hiring a Senior Data Engineer who builds systems that survive production and ships products that customers pay for:

[![Email Me](https://img.shields.io/badge/Email_Me-iamravikantpal%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iamravikantpal@gmail.com)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ravikant-pal)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
