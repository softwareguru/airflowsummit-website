---
title: "Declarative Pipelines Meet Declarative Orchestration: Spark Declarative Pipelines + Airflow 3"
slug: declarative-pipelines-meet-declarative-orchestration-spark-declarative-pipelines-airflow-3
speakers:
 - Lisa Cao
 - Andreas Neumann
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Apache Spark's new Declarative Pipelines (SDP) let engineers define WHAT their data should look like, not HOW to build it. Apache Airflow 3 brings a declarized orchestration model. Together, they eliminate an entire category of boilerplate: the DAG that exists only to babysit a pipeline. This talk walks through building a production Spark SDP pipeline orchestrated by Airflow 3, showing how dependency graphs replace imperative task chains, how testing and recovery patterns change when your pipeline is declarative end-to-end, and what this means for the 80% of data engineering time currently spent on operational plumbing. 