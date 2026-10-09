---
title: "Configuration-Driven Data Pipelines: dbt + Airflow + Cosmos"
url: onlinereconnect/configuration-driven-data-pipelines/
speakers:
 - Suba Palanisamy
 - Sushmita Barthakur
 - Sneha Rao
track: Builder
room: Online
#day: 2026o1
time_start: 2026-11-04 15:00:00
time_end: 2026-11-04 15:30:00
timeslot: 
gridarea: 
images: 

slides:
video: 
---

Most data teams start by hand-writing Airflow DAGs for each dbt model. It works at first — then you hit 50 models, 100 models, and suddenly you're maintaining more orchestration code than transformation logic. DAG sprawl becomes the bottleneck.

Astronomer Cosmos solves this by auto-generating Airflow tasks directly from your dbt project. Combined with configuration-driven patterns, you go from a new SQL model to a fully orchestrated, tested, lineage-tracked pipeline with zero DAG code.

This session shares hands-on techniques for building this in production:

Cosmos integration: auto-generating tasks from dbt models with dependency awareness
Configuration-driven design: YAML metadata controlling scheduling, alerting, and dependencies
Testing patterns: dbt tests as Airflow tasks with failure-aware routing
Lineage and observability: tracking data flow from source to dashboard
Scaling: managing hundreds of models without DAG maintenance overhead
Migration: moving from hand-written DAGs to Cosmos incrementally

You leave with a reusable framework for configuration-driven pipelines — no more boilerplate DAGs, applicable to any Airflow deployment.