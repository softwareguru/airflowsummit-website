---
title: "Micropipelines: A microservice approach for DAG authoring using datasets"
slug: micropipelines-a-microservice-approach-for-dag-authoring-using-datasets
speakers:
 - Vikram Koka
time_start: 2023-09-20T15:00:00-04:00
time_end: 2023-09-20T15:30:00-04:00
room: Ballroom A-B
track: Operationalizing Airflow
day: 2
timeslot: 11
---

Introduced in Airflow 2.4, Datasets are a foundational feature for authoring modular data pipelines. As DAGs grow to encompass a larger number of data sources and encompass multiple data transformation steps, they typically become less predictable in the timeliness of execution and less efficient. 
 
 
 
 This talk focuses on leveraging Datasets to enable predictable and more efficient DAGs, by leveraging patterns from microservice architectures. Just as large monolithic applications were decomposed into micro-services to deliver more efficient scalability and faster development cycles, micropipelines have the same potential to radically transform data pipeline efficiency and development velocity. 
 
 
 
 Using a simple financial analysis pipeline example, with data aggregation being done in Snowflake and prediction analysis in Spark, this talk outlines how to retain timelines of data pipelines while expanding data sets.