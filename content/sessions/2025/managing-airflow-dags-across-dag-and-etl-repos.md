---
title: "Managing Airflow DAGs Across DAG and ETL Repos"
slug: managing-airflow-dags-across-dag-and-etl-repos
speakers:
 - Yunhao Qing
topics:
 - Use cases
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
images:
 - /images/sessions/2025/managing-airflow-dags-across-dag-and-etl-repos.png
---

At Lyft, we manage Airflow DAGs across both the ETL and DAG repos, each serving distinct needs. The ETL repo is ideal for simple use cases and users with only a few DAGs, offering a streamlined workflow. Meanwhile, the DAG repo supports power users with numerous DAGs, custom dependencies, and complex ML pipelines. In this session, I’ll share how we structure these repos, the trade-offs involved, and best practices for scaling Airflow DAG management across diverse teams and workloads.