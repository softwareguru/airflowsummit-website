---
title: "Adaptive DAGs: Dynamic Query Plan Rewriting and Runtime Task Re-sizing in Airflow"
slug: adaptive-dags-dynamic-query-plan-rewriting-and-runtime-task-re-sizing-in-airflow
speakers:
 - Satej Sahu
track: Builder
room: Online
day: 2026o2
time_start: 2026-11-05 13:30:00
time_end: 2026-11-05 14:00:00
timeslot: 6
gridarea: 7/2/8/8
slides: 
video:
---

Traditional Airflow DAGs execute rigid, pre-determined computation graphs. Yet in production, data volume and distribution fluctuate wildly: a daily ingestion batch may process 50,000 rows on Monday but 50,000,000 on Black Friday. Statically sized tasks force engineers into a painful compromise: either permanently over-provision worker resources (blowing cloud budgets) or risk out-of-memory crashes, disk spills, and missed SLAs during unexpected volume spikes.

Drawing inspiration from database query optimizer research and recent papers on learned adaptive pipeline scheduling, this technical session demonstrates how to implement Adaptive DAGs in Apache Airflow. We show how to construct workflows that introspect upstream intermediate data statistics to dynamically adjust downstream execution plans, engine targets, and parallelism at runtime. Attendees will learn:

1. Runtime Plan Profiling: Using lightweight metadata collectors and storage manifests (Iceberg/Delta metadata) to capture data volume, partition skew, and cardinality before heavy compute stages run.
2. Dynamic Strategy Routing: Leveraging Airflow's TaskFlow API and Dynamic Task Mapping (.expand()) to conditionally route jobs between lightweight single-node compute (DuckDB/Polars) for small datasets and distributed clusters (Spark/Ray) for large scale.
3. Adaptive Partition Resizing: Dynamically generating downstream worker parallelism and memory allocations on the fly, eliminating OOM failures and compute waste.

Attendees will leave with production-ready code patterns to build self-tuning, resilient Airflow pipelines.