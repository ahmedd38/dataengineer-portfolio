# 📊 Data Engineer Portfolio

A practical portfolio of data engineering pipelines, orchestrated DAGs, and analytics notebooks. These projects demonstrate end-to-end ETL processes, real-time ingestion, data lake design, and Python-based transformations.

## 📌 Highlights
- Apache Airflow DAG orchestration
- Batch and streaming ETL pipelines
- Python & Pandas-based data wrangling
- Data validation and unit testing
- Jupyter notebooks with visual insights

## Project List

## 1. Smart Grid IoT Data Pipeline

### Problem
Power companies in emerging markets struggle to track real-time grid performance.

### Solution
Build an end-to-end pipeline that:
- Ingests data from simulated smart meters via **AWS Kinesis**
- Transforms with **AWS Glue** + **Apache Hudi**
- Loads into **Redshift**
- Visualized in **Amazon QuickSight**

### Goals
- Stream real-time energy usage
- Aggregate usage by time, region, household
- Detect anomalies and outages

---

## 2. Kenya Open Data Explorer

### Problem
Government data is available but not easily analyzable for citizens or journalists.

### Solution
Create a public analytics dashboard:
- ETL pipelines in **Apache Airflow**
- Cleaned datasets in **BigQuery**
- Visualizations in **Metabase**
- Public search and filter frontend using **Next.js**

### Goals
- Process and publish monthly updated datasets
- Make visual data stories (health, education, environment)
- Enable CSV downloads and API access

---

## 3. Political Sentiment Analysis Pipeline

### Problem
Election stakeholders need real-time sentiment insights from social media.

### Solution
Stream political tweets and comments:
- **Kafka** or **Kinesis Firehose** for ingestion
- **Spark Structured Streaming** for processing
- **S3** + **PrestoDB** for storage and querying
- Dashboard built with **Apache Superset**

### Goals
- Classify sentiments: positive, neutral, negative
- Track by politician, region, or hashtag
- Show trending concerns or hate speech
