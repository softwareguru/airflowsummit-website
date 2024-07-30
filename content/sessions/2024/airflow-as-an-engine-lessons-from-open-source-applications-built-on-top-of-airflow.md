---
title: "Airflow as an Engine: Lessons from open-source applications built on top of Airflow"
slug: airflow-as-an-engine-lessons-from-open-source-applications-built-on-top-of-airflow
speakers:
 - Ian Moritz
track:
 - Community
images:
 - /images/sessions/2024/airflow-engine.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Airflow is often used for running data pipelines, which themselves connect with other services through the provider system. However, it is also increasingly used as an engine under-the-hood for other projects building on top of the DAG primitive. For example, Cosmos is a framework for automatically transforming dbt DAGs into Airflow DAGs, so that users can supplement the developer experience of dbt with the power of Airflow.

This session dives into how a select group of these frameworks (Cosmos, Meltano, Chronon) use Airflow as an engine for orchestrating complex workflows their systems depend on. In particular, we will discuss ways that we’ve increased Airflow performance to meet application-specific demands (high-task-count Cosmos DAGs, streaming jobs in Chronon), new Airflow features that will evolve how these frameworks use Airflow under the hood (DAG versioning, dataset integrations), and paths we see these projects taking over the next few years as Airflow grows. Airflow is not just a DAG platform, it’s an application platform!