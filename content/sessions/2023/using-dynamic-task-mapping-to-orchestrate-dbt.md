---
title: "Using Dynamic Task Mapping to Orchestrate dbt"
slug: using-dynamic-task-mapping-to-orchestrate-dbt
speakers:
 - Pádraic Slattery
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Use cases
session_type: breakout
---

Airflow, traditionally used by Data Engineers, is now popular among Analytics Engineers who aim to provide analysts with high-quality tooling while adhering to software engineering best practices. dbt, an open-source project that uses SQL to create data transformation pipelines, is one such tool. One approach to orchestrating dbt using Airflow is using dynamic task mapping to automatically create a task for each sub-directory inside dbt's staging, intermediate, and marts directories. This enables analysts to write SQL code that is automatically added as a dedicated task in Airflow at runtime. Combining this new Airflow feature with dbt best practices offers several benefits, such as analysts not needing to make Airflow changes and engineers being able to re-run subsets of dbt models should errors occur. In this talk, I would like to share some lessons I have learned while successfully implementing this approach for several clients.