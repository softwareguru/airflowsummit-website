---
title: "Dynamic Data Pipelines with DBT and Airflow"
slug: dynamic-data-pipelines-with-dbt-and-airflow
speakers:
 - Miquel Angel Andreu Febrer
topics:
 - Use cases
time_start: 2025-10-08 10:30:00
time_end: 2025-10-08 11:10:00
room: Beckler
track: Use cases
day: 20252
timeslot: 44
gridarea: 4/5/5/6 
images:
slides:
video:
---

This session showcases Okta's innovative approach to data pipeline orchestration with dbt and Airflow. How we've implemented dynamically generated airflow dags workflows based on dbt's dependency graph. This allows us to enforce strict data quality standards by automatically executing downstream model tests before upstream model deployments, effectively preventing error cascades. The entire CI/CD pipeline, from dbt model changes to production DAG deployment, is fully automated. The result? Accelerated development cycles, reduced operational overhead, and bulletproof data reliability