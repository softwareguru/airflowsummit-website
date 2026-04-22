---
title: "A SQL Query is Just a DAG: Building a SQL Engine on Apache Airflow"
slug: a-sql-query-is-just-a-dag-building-a-sql-engine-on-apache-airflow
speakers:
 - Hussein Awala
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Ever wondered what happens between typing `SELECT ... GROUP BY` and getting results back? Inside every SQL engine lives a scheduler that breaks your query into a DAG of tasks — shuffling, sorting, aggregating, and parallelizing work across partitions. Sound familiar?

In this talk, I'll demystify SQL engine internals by building one on top of Apache Airflow. We'll take a SQL query, parse it, optimize it, and transform it into a DAG of Airflow tasks that you can watch execute step by step in the Airflow UI.

You'll walk away understanding:
- How SQL engines plan and schedule query execution
- What shuffle, partition, and pipeline-breaking actually mean
- How query parallelism works under the hood

No PhD in databases required — just curiosity and an Airflow UI to watch it all unfold.