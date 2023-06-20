---
title: "Data Product DAGs"
slug: data-product-dags
speakers:
 - Charles Verleyen
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
session_type: breakout

---

This talk will cover in high overview the architecture of a data product DAG, the benefits in a data mesh world and how to implement it easily.



Airflow is the de-facto orchestrator we use at Astrafy for all our data engineering projects. Over the years we have developed deep expertise in orchestrating data jobs and recently we have adopted the “data mesh” paradigm of having one Airlfow DAG per data product. Our standard data product DAGs contain the following stages:



- Data contract: check integrity of data before transforming the data

- Data transformation: applies dbt transformation via a kubernetes pod operator

- Data distribution: mainly informing downstream applications that new data is available to be consumed



For use cases where different data products need to be finished before triggering another data product, we have a mechanism with an engine in between that keeps track of finished dags and triggers DAGs based on a mapping table containing data products dependencies.