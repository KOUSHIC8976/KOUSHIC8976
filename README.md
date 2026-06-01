<div align="center">
  <h1>Hello, I'm KOUSHIC </h1>
  <h3>Data Engineer | Modern Data Stack | IaC</h3>
  <p><i>Building reliable, decoupled, and production-grade data pipelines.</i></p>

  <a href="https://www.linkedin.com/in/b-koushic/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="mailto:koushic5206@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</div>

---

###  About Me

Junior Data Engineer specializing in building reliable, production-style data pipelines using SQL, dbt, Airflow, and AWS. Developed an end-to-end analytics platform with idempotent ingestion, backfill handling, data quality checks, and cloud-based deployment. Familiar with Infrastructure-as-Code (Terraform) and containerized workflows (Docker). Focused on delivering stable, cost-aware, and scalable data systems.

---

###  Technical Skills

| Category | Stack |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnu-bash&logoColor=white) |
| **Orchestration & Transformation** | ![Airflow](https://img.shields.io/badge/-Apache%20Airflow-017CEE?logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?logo=dbt&logoColor=white) ![Great Expectations](https://img.shields.io/badge/-Great%20Expectations-EA526F?logo=python&logoColor=white)|
| **Streaming & Event Processing**| ![Kafka](https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&logoColor=white) ![Flink](https://img.shields.io/badge/-Apache%20Flink-E6522C?logo=apacheflink&logoColor=white) |
| **Compute & Storage** | ![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?logo=duckdb&logoColor=black) ![Iceberg](https://img.shields.io/badge/-Apache%20Iceberg-231F20?logo=apache&logoColor=white) |
| **Infra & DevOps** | ![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) |

---

### 📂 Featured Projects

####  [PermuteX: Real-Time Streaming Pipeline](https://github.com/koushic8976/permutex)
**Architecture:** `Python` • `Kafka (KRaft)` • `Apache Flink` • `PostgreSQL` • `Grafana`
* Built a decoupled, real-time streaming architecture to process continuous IoT telemetry data using Kafka and stateful Apache Flink (PyFlink) tumbling windows.
* Prevented downstream pipeline failures by enforcing Avro data contracts via Confluent Schema Registry.
* Orchestrated automated Airflow anomaly-detection jobs against a live PostgreSQL serving layer, integrated with Grafana for sub-second observability.

####  [RERA: Robustness Certification Data Pipeline](https://github.com/koushic8976/rera)
**Architecture:** `Python` • `PyTorch` • `Docker` • `MLOps` • `DAG Orchestration`
* Built a GPU-accelerated data orchestration pipeline for autonomous systems, reducing simulation bottlenecks by parallelizing 1M+ Bayesian tensor evaluations in local VRAM.
* Processed complex vehicle telemetry using Directed Acyclic Graphs (DAGs) to transition from data correlation to causal root-cause extraction.
* Decoupled the infrastructure into a deployable **Docker** container, generating automated JSON compliance artifacts and HTML dashboards for CI/CD integration.

####  [Ledger Sync: Logistics SLA Lakehouse](https://github.com/koushic8976/ledger-sync)
**Architecture:** `Airflow` • `Kafka` • `dbt` • `DuckDB` • `AWS S3` • `Terraform`
* Designed an end-to-end Medallion data pipeline using Apache Airflow to ingest, cleanse, and transform streaming logistics telemetry from Apache Kafka into AWS S3.
* Engineered a decoupled compute architecture utilizing **DuckDB** for in-memory processing and **dbt** for advanced SQL transformations to track delivery SLA breaches.
* Built a resilient data contract layer using **Great Expectations** to filter corrupted IoT sensor data without pipeline bottlenecks.

####  [AutoMQ-Flink-Streaming](https://github.com/koushic8976/AutoMQ-Flink-Streaming)
**Architecture:** `Python` • `AutoMQ` • `Apache Kafka` • `S3` •`Apache Flink`
* A proof-of-concept demonstrating a seamless migration from traditional KRaft Kafka to AutoMQ (S3-backed storage) with exactly zero lines of code changed in the Apache Flink downstream compute layer with PermuteX as foundation.

####  [Code Cartographer](https://github.com/koushic8976/code-cartographer)
**Architecture:** `Python` • `AST` • `Gemini API` • `HuggingFace` • `Code-BERT`
* A developer tool designed to instantly reverse-engineer and visually map legacy or undocumented Python codebases by parsing Abstract Syntax Trees (AST) into deterministic dependency graphs.

---

