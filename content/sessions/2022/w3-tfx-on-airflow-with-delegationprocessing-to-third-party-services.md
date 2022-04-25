---
id: w3
title: "TFX on Airflow with delegation of processing to third party services"
url: /sessions/2022/tfx-on-airflow-with-delegationprocessing-to-third-party-services
speakers:
 - Israel Herraiz
 - Paul Balm
time_start: 2022-05-27T01:30:00.000Z
time_end: 2022-05-27T04:00:00.000Z
format: "Workshop"
hosted_by: "Workshop 3"
presence: "remote"
block: w
slot: 3
---

Tensorflow Extended (TFX) can run machine learning pipelines on Airflow, but all the steps are run by default in the same workers where the Airflow DAG is running. This can lead to an excessive usage of resources, and breaks the assumption that Airflow is a scheduler; it becomes also the data processing platform. In this talk, we will see how to use TFX with third party services, on top of Google Cloud Platform. The data processing steps can be run in Dataflow, Spark, Flink and other runners (parallelizing the processing of data and scaling up to petabytes), and the training steps can be run in Vertex or other external services. 
 
 
 
 After this workshop, you will have learnt how to externalize any TFX heavyweight computing outside Airflow, while maintaining Airflow as the orchestrator for your machine learning pipelines.