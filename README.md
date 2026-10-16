<h1 align="center">Hi, I'm Danish 👋</h1>
<p align="center"><b>Muhammad Danish Ishfaq · Data Architect / Principal Data Engineer</b><br>
Nearly 9 years in data. MS Computer Science, University of Eastern Finland. I've worked in Pakistan, Estonia and Finland.</p>

<p align="center">
<a href="mailto:daneshrana45@gmail.com"><img src="https://img.shields.io/badge/Email-daneshrana45%40gmail.com-0a0e1a?style=for-the-badge&logo=gmail&logoColor=7aa2ff"></a>
<a href="https://www.linkedin.com/in/danish-rajput/"><img src="https://img.shields.io/badge/LinkedIn-Danish-0a66c2?style=for-the-badge&logo=linkedin"></a>
<a href="https://muhammaddanish122.github.io"><img src="https://img.shields.io/badge/Portfolio-visit-3ddc97?style=for-the-badge&logo=githubpages&logoColor=white"></a>
</p>

🌐 **Portfolio:** https://muhammaddanish122.github.io

### What I do
I build pipelines that move data out of busy transactional systems into analytics without losing rows. Right now that means real-time CDC from MySQL through Debezium and Kafka into ClickHouse, plus the tooling to run it.

Before this I was at Pipedrive in Estonia (dbt + Iceberg migration, 40% faster queries), Teradata, and Sulzer Pumps in Finland. Earlier on I built a Kafka streaming platform for Emirates Digital Banking and IoT pipelines on AWS.

### Flagship: Kafka Manager / CDC Pipeline Manager
**[kafka-cdc-platform](https://github.com/MuhammadDanish122/kafka-cdc-platform)**: a FastAPI + JS control room for a 200+ table CDC pipeline. It handles consumer controls, tracing a record across all partitions, topic backups, dedup jobs and binlog-based DML stats.

<img src="https://raw.githubusercontent.com/MuhammadDanish122/kafka-cdc-platform/main/assets/architecture.svg" width="100%">
<img src="https://raw.githubusercontent.com/MuhammadDanish122/kafka-cdc-platform/main/assets/screens/km_mysql_stats_overview.png" width="100%">

### What I bring as an architect
- End-to-end CDC design: HA across KRaft, Connect and consumer groups, ack-then-commit delivery, gated tag-based releases
- A ClickHouse real-time warehouse with layered topics (raw → processed → BI), versioned tables and automatic schema drift
- Warehouses and marts on Azure SQL DW, dbt/Iceberg, Fabric, Teradata, Redshift/Hive and SQL Server

### Other work
- Moved Signal (US, Walmart security) from Databricks + Azure SQL DW + ADF to Microsoft Fabric
- Pipedrive: legacy PySpark → dbt + Apache Iceberg on S3/Athena with Airflow, 40% better query performance
- Teradata warehouse, plus a sensor pipeline with NiFi, Spark and Airflow into Redshift/Hive
- Sitara Textile SQL Server EDW with SSIS and Power BI

### Stack
<p>
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white">
<img src="https://img.shields.io/badge/Debezium-91D443?style=flat-square&logoColor=black">
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white">
<img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white">
<img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white">
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white">
<img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white">
<img src="https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/Teradata-F37440?style=flat-square&logo=teradata&logoColor=white">
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
</p>

**Certs:** Teradata Vantage Associate · IBM Big Data, Hadoop, Hive, Spark, Python for Data Science, SQL

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=MuhammadDanish122&show_icons=true&theme=tokyonight&hide_border=true" height="160"></p>
