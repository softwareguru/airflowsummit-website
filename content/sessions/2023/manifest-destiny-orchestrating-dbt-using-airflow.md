---
title: "Manifest destiny: Orchestrating dbt using Airflow"
slug: manifest-destiny-orchestrating-dbt-using-airflow
speakers:
 - Jonathan Talmi
time_start: 2023-09-20T15:00:00-04:00
time_end: 2023-09-20T15:25:00-04:00
room: Ballroom crush
track: Airflow & ...
day: 2
timeslot: 11
---

Airflow is a popular choice for organizations looking to integrate open-source dbt within their existing data infrastructure. This talk will explore two primary methods of running dbt in Airflow: job-level and model-level. We'll discuss the tradeoffs associated with each approach, highlighting the simplicity and efficiency of job-level orchestration, contrasted with the enhanced observability and control provided by model-level orchestration. We'll also explain how the balance has shifted in recent years, with improvements to dbt core making model-level more efficient and innovative Airflow extensions like Cosmos making it easier to implement. Finally, we'll provide benchmarks to help you determine which paradigm is the best fit for your needs.