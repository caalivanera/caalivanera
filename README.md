## Hi, I'm Charles Alivanera 👋

I'm a highly analytical professional building a career in Data Engineering. My journey has taken me from solving high-stakes customer escalations for major accounts like **Airbnb** and **AT&T** to my current technical role.

As a Data and Reports Analyst supporting the healthcare analytics company **Aetion**, I perform core data engineering tasks, including **ETL, data pipeline optimization, and analysis using Python, R, and AWS**.

I'm now expanding on this hands-on experience by executing an intensive learning plan to master the modern data stack. My goal is to build robust, scalable, and automated systems that transform raw data into business value.

---

### 🚀 Key Tech Stack

| Warehousing | Transformation | Orchestration | Big Data & Streaming | DataOps (IaC) | Cloud |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Snowflake | dbt | Apache Airflow | Apache Spark (PySpark) | Terraform | AWS |
| BigQuery | Spark SQL | Databricks Workflows | Apache Kafka | Docker | GCP |
| Delta Lake | Python (Pandas) | Shell Scripting | PySpark Streaming | Kubernetes | Azure |

---

### 🌱 My 8-Month Data Engineering Master Plan

I am currently executing an 8-month plan (starting Dec. 2025) to gain deep, job-ready expertise in the complete data lifecycle.

* **Months 1-2: The Modern Warehouse:** Mastering the Lakehouse (Spark, Databricks, Delta Lake) and the Warehouse (Snowflake, dbt, Snowpark).
* **Months 3-4: The Open-Source Foundation:** Mastering pipeline fundamentals (Linux, Bash, Airflow, Kafka) and database variety (PostgreSQL Admin, NoSQL).
* **Months 5-7: The Senior-Level Toolkit:** Mastering DataOps (Docker, Kubernetes, Terraform), Agile Project Management (Jira, Confluence), and Technical Documentation.
* **Month 8: The Portfolio:** Synthesizing all skills into the capstone projects detailed below.

---

### 💻 Portfolio: Bridging Business Problems & Technical Solutions

These projects are where I am applying my skills to solve realistic business problems.

#### 1. (In Progress) Predictive Churn & CLV Analysis for Telecom
* **Repository:** `telecom-churn-analytics-dashboard`
* **Business Problem (User Story):** "As a retention manager for a major telecom, we need to proactively identify high-value accounts at risk of churning and understand the root cause of escalations to improve Customer Lifetime Value (CLV)."
* **Tech Stack & Architecture:**
    * **Analysis:** Built a predictive churn model using **R** and **SQL** to score a portfolio of 1,200+ high-value accounts.
    * **BI & Visualization:** Developed a **Tableau** and **Power BI** framework to transform raw data from million-record CRM datasets into actionable insights.
    * **Impact:** This analysis directly informed data-driven retention campaigns, helped reduce voluntary churn by 8%, and identified opportunities that drove a 15% uplift in CLV.

#### 2. (In Progress) The Modern Batch ETL Pipeline
* **Repository:** `modern-healthcare-elt-pipeline`
* **Business Problem (User Story):** "As a data analyst, we need a reliable, automated, and tested daily pipeline to load clinic CSV reports into our warehouse for visualization."
* **Tech Stack & Architecture:**
    * **Orchestration:** **Apache Airflow** (run locally via Docker) to schedule and manage the pipeline.
    * **Ingestion:** Python scripts to extract/load CSV data into **Snowflake**.
    * **Transformation:** **dbt Core** (triggered by Airflow's `BashOperator`) to run models (`dbt run`) and data quality tests (`dbt test`).
    * **DataOps (IaC):** **Terraform** to provision and manage all cloud infrastructure (e.g., S3/GCS buckets, Snowflake datasets, service accounts) as code.

#### 3. (In Progress) The Real-Time Streaming Pipeline
* **Repository:** `real-time-patient-streaming`
* **Business Problem (User Story):** "Our clinical team wants to monitor patient-reported outcomes from our mobile app in real-time to detect high-symptom alerts."
* **Tech Stack & Architecture:**
    * **Producer:** **Apache Kafka** (run locally via Docker) to ingest a stream of JSON events.
    * **Simulator:** A Python script (`producer.py`) to simulate app events and send them to the Kafka topic.
    * **Processing:** A **PySpark** Structured Streaming application in a **Databricks** notebook to consume from Kafka, filter for alerts (`symptom_score > 7`), and perform transformations.
    * **Storage:** Writing the processed alerts in real-time to a **Delta Lake** table for analysis.

---

### 📫 How to reach me:

* **LinkedIn:** [linkedin.com/in/caalivanera](https://www.linkedin.com/in/caalivanera)
* **Email:** `caalivanera@gmail.com`
