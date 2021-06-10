---
id: b1
title: "Dataclasses as Pipeline Definitions in Airflow"
url: /sessions/2021/dataclasses-as-pipeline-definitions
speakers:
 - Madison Swain-Bowden
time_start: 2021-07-13T04:00:00.000Z
time_end: 2021-07-13T04:25:00.000Z
block: b
slot: 1
format: presentation
aliases:
 - /sessions/Dataclasses-as-Pipeline-Definitions-in-Airflow
---

We will describe how we were able to build a system in Airflow for MySQL to Redshift ETL pipelines defined in pure Python using dataclasses. These dataclasses are then used to dynamically generate DAGs depending on pipeline type. This setup allows us to implement robust testing, validation, alerts, and documentation for our pipelines. We will also describe the performance improvements we achieved by upgrading to Airflow 2.0.