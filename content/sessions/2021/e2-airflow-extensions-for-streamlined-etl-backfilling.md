---
id: e2
title: "Airflow Extensions for Streamlined ETL Backfilling"
url: /sessions/2021/airflow-extensions-for-streamlined-etl-backfilling
speakers:
 - Ravi Autar
time_start: 2021-07-15T04:30:00.000Z
time_end: 2021-07-15T04:55:00.000Z
block: e
slot: 2
format: presentation
crowdcast_id: 33
video: https://youtu.be/p4JpHFR932I
---

Using Airflow as our scheduling framework, we ETL data generated by tens of millions of transactions every day to build the backbone for our reports, dashboards, and training data for our machine learning models. There are over 500 (and growing) such ingested and aggregated tables owned by multiple teams that contain intricate dependencies between one another. Given this level of complexity, it can become extremely cumbersome to coordinate backfills for any given table, when also taking into account all its downstream dependencies, aggregation intervals, and data availability. This talk will focus on how we customized and extended Airflow at Adyen to streamline our backfilling operations. This allows us to prevent mistakes and enable our product teams to keep launching fast and iterating.
