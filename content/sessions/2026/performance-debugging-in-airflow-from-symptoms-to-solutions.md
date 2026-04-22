---
title: "Performance Debugging in Airflow: From Symptoms to Solutions"
slug: performance-debugging-in-airflow-from-symptoms-to-solutions
speakers:
 - Rahul Vats
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Airflow running slow? Memory is spiking. Tasks are queuing forever. Now what?
Debugging performance issues in a distributed system like Airflow can feel overwhelming—is it the scheduler, the database, the DAG Processor, or your DAG code? This talk shares practical techniques for isolating and fixing performance problems, using real examples from the Airflow codebase.

We'll cover:
1. Understanding Airflow's moving parts – Where bottlenecks typically hide (scheduler loop, DAG parsing, database queries).

2. Profiling techniques – Memory profiling, query analysis, and metrics that actually matter.

3. Case study: DAG Processor OOM – How a single SQLAlchemy query caused a memory explosion, and how we fixed it.

4. Testing your fixes – Setting up reproducible performance tests before and after.

Whether you're troubleshooting your own deployment or contributing fixes upstream, you'll leave with a toolkit for tackling Airflow performance issues.