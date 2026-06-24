# Hi, I am Rohith

Analytics Engineering · BI & Visualization · AI Agents · Cloud Infrastructure

---

## Tech Stack

**Data Engineering & Warehouses:** dbt · Apache Airflow · PySpark · AWS Glue · PostgreSQL · MS SQL · Snowflake · BigQuery · Redshift · Python
**AI/ML:** RAG · LangGraph · OpenAI API · Ollama · pgvector · ChromaDB
**Cloud:** AWS · Azure
**BI & Visualization:** Power BI · Tableau · Looker Studio

---

## Background

MBA in Big Data Analytics. 4 years at a data consulting firm delivering end-to-end data projects across **BFSI, pharma, retail, and SaaS** — spanning data engineering, BI, and analytics across US, UK, and Sri Lanka markets.

Managed engagements end-to-end — from scoping and SOW through delivery and closure — balancing hands-on technical delivery with client stakeholder management.

---

## Work samples

Recurring patterns from client engagements, rebuilt as sample solutions with synthetic data.

| Project | Description | Stack | Demo |
|---------|-------------|-------|------|
| [dbt Metrics Layer — Pharma KPI Governance](https://github.com/ro-kannan/dbt-metricflow-pharma-analytics-governance) | Five teams, one KPI, five different answers — a Semantic Layer that enforces a single definition. | dbt · MetricFlow · DuckDB · Streamlit | [Live](https://dbt-metricflow-pharma-analytics-governance.streamlit.app) |
| [Event-Driven Order Ingestion Pipeline](https://github.com/ro-kannan/serverless-order-ingestion-pipeline) | File upload triggers a serverless pipeline — validates two order sources, quarantines bad batches, loads idempotently. | AWS EventBridge · Step Functions · Lambda · RDS PostgreSQL · Python | — |
| [Airflow Retail Order Pipeline — AWS S3 Dead-Letter](https://github.com/ro-kannan/airflow-retail-pipeline-aws) | Omnichannel orders from two sources hit a quality gate — clean rows load to analytics, bad rows are quarantined to S3 before they reach the database. | Apache Airflow · AWS S3 · PostgreSQL · Docker · Python | — |
| [Multi-Consumer AI Data Gateway](https://github.com/ro-kannan/multi-consumer-ai-data-gateway) | The controlled layer between AI agents and your database — per-consumer auth, rate limits, and validated SQL execution. | FastAPI · SQLAlchemy · PostgreSQL · Python | — |
| [SCD Type 2 — Lending Dimension](https://github.com/ro-kannan/scd-type2-lending) | Historical reports silently return wrong numbers when a dimension attribute changes — because the join returns today's value, not what it was at the time. SCD Type 2 fixes this. | dbt · PostgreSQL · Python | — |
| [On-Prem to Cloud Migration](https://github.com/ro-kannan/aws-snowflake-onprem-migration) | Full on-prem to cloud migration: incremental extraction, automated on a schedule, and a dbt transformation layer handling the migration seamlessly. | AWS · Snowflake · EC2 · dbt | — |
| [Analytics Engineering — E-commerce Pipeline](https://github.com/ro-kannan/analytics-eng-dbt-ecommerce) | Transforms raw e-commerce transaction logs into reliable dbt marts — incremental loads, 16 data quality tests, and automatic alerts when source data goes stale. | dbt · PostgreSQL · Python | — |

---
