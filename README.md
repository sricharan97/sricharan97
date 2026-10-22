# Charan Konduri
**Senior Data Engineer** — designing reliable AWS data pipelines, orchestration, lakehouse platforms, and warehouses.

## About Me
I'm **Charan Konduri** ([@sricharan97](https://github.com/sricharan97)), a Senior Data Engineer focused on building dependable pipelines, medallion lakehouse architectures on AWS, and dimensional warehouse models.

At **IBM**, I've been responsible for the reliability of **20+ enterprise applications**, owned **hundreds of automated scripts**, and worked across system design, performance optimization, and process automation — with a strong emphasis on high uptime. That operational rigor is what I now bring to data engineering: clear lineage, reproducible runs, and pipelines that stay maintainable as they grow.

I completed the **Udacity Data Engineering with AWS Nanodegree**, including the **Data Pipelines with Airflow** project (submitted and passed). Alongside data engineering, I bring additional skills in Android development through the Google Android Kotlin Nanodegree and the Meta Android Developer Professional Certificate — and I enjoy building mobile apps as a side hobby every now and then.

## Tech Stack
- **Languages:** Python, SQL
- **Orchestration & compute:** Apache Airflow (Assets), Spark / AWS Glue jobs
- **AWS & lakehouse:** S3, S3 Tables, Glue, Athena, Lake Formation, CloudFormation / IAM, Apache Iceberg
- **Warehousing & modeling:** Amazon Redshift (Serverless, Data API), dimensional / star-schema design, 3NF
- **Databases:** PostgreSQL, MongoDB, Neo4j, Cassandra
- **Tooling:** Jupyter, pandas, Docker Compose
- **Also:** Kotlin / Android (mobile apps as a side hobby)

## Featured Projects
- **[Sparkify Airflow Lakehouse](https://github.com/sricharan97/sparkify-airflow-lakehouse)** — Data Engineering portfolio project from the Udacity DE with AWS Nanodegree. Medallion lakehouse (**raw → transactions → analytics**) orchestrated with Airflow Assets, stored as Iceberg tables, and queryable via Athena — with Glue jobs, S3 landing/warehouse paths, and CloudFormation for infrastructure.
- **[Exastore Iceberg Lakehouse](https://github.com/sricharan97/exastore-iceberg-lakehouse)** — Bronze → Silver → Gold lakehouse for e-commerce data on AWS Glue 5.0, Apache Iceberg, S3 Tables, and Athena. Ingests PostgreSQL CDC records (Debezium JSON) with deduplicated `MERGE INTO` upserts, loads clickstream events with data-quality checks, builds business-ready metrics, and demonstrates Iceberg snapshots and time travel.
- **[Unified Commerce Redshift Warehouse](https://github.com/sricharan97/unified-commerce-redshift-warehouse)** — Multi-source analytics warehouse on Amazon Redshift that unifies PostgreSQL orders, Cassandra clickstream, and Neo4j recommendation edges into a star schema (staging → 12 dimensions → 3 facts). Includes distribution/sort-key design, a daily-revenue materialized view, and validated analytical queries, loaded through the Redshift Data API.
- **[ACME Data Modeling](https://github.com/sricharan97/acme-data-modeling)** — Data modeling across three stores: a 3NF PostgreSQL OLTP schema, a MongoDB document model for a 3D-printing catalog, and a Neo4j recommendation graph (with an optional GraphRAG helper). Runs locally with Docker Compose.

### Other data work
- **[Amazon E-Commerce Data Analysis](https://github.com/sricharan97/amazon-ecommerce-data-analysis)** — Exploratory analysis of the Amazon Reviews 2023 Electronics dataset: streams a 22.6 GB dataset, applies quality filters, exports CSV/Parquet, and visualizes the results (pandas, matplotlib, seaborn).

### Mobile apps (side projects)
- **[FitStreak](https://github.com/sricharan97/FitStreak)** — Fitness tracker with Google Fit and Firebase auth (Kotlin, Jetpack Compose, MVVM).
- **[Location Reminder](https://github.com/sricharan97/LocationReminder)** — Geofencing task reminders with Google Maps.

## Certifications
- **Udacity Data Engineering with AWS Nanodegree** — Capstone-style project: Data Pipelines with Airflow (submitted and passed).
- **Google Android Kotlin Developer Nanodegree** — Udacity.
- **Meta Android Developer Professional Certificate** — Coursera.

## Let’s Connect
- **LinkedIn:** [charankonduri](https://www.linkedin.com/in/charankonduri)
- **Portfolio:** [charankonduri.com](https://charankonduri.com)

Open to conversations about data engineering roles, pipeline design, and collaboration.
