---
title: "Spark + Airflow: How Orchestration Decisions Impact Performance and Cost"
slug: spark-airflow-how-orchestration-decisions-impact-performance-and-cost
speakers:
 - Meni Shmueli
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Apache Airflow is the de facto orchestrator for modern data platforms, while Apache Spark powers large-scale data processing. But when the two meet in production, teams quickly face architectural decisions that affect reliability, performance, and cloud cost.

In this talk we explore key design questions when orchestrating Spark with Airflow:
	•	Should you run a shared Spark cluster, a cluster per DAG run, or clusters per task?
	•	When should Spark workloads run in parallel vs sequentially within a workflow?
	•	How can teams benchmark pipeline performance in terms of both runtime and cost?
	•	How do emerging features like Spark Declarative Pipelines change how Spark integrates with orchestration systems?

Using real production scenarios, we’ll examine the tradeoffs between orchestration strategies and show how Spark observability with DataFlint OSS helps analyze execution plans, task behavior, and runtime metrics.

We’ll also demonstrate how propagating Airflow metadata into Spark jobs allows teams to attribute infrastructure usage and cost back to individual DAGs and benchmark workflow performance.