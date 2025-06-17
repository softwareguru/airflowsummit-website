---
title: "Benchmarking the Performance of Dynamically Generated DAGs"
slug: benchmarking-the-performance-of-dynamically-generated-dags
speakers:
 - Tatiana Al-Chueyr Martins
 - Rahul Vats
topics:
 - Best practices
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

As teams scale their Airflow workflows, a common question is: "My DAG has 5,000 tasks—how long will it take to run in Airflow?"

Beyond execution time, users often face challenges with dynamically generated DAGs, such as:
* Delayed visualization in the Airflow UI after deployment.
* High resource consumption, leading to Kubernetes pod evictions and out-of-memory errors.

While estimating the resource utilization in a distributed data platform is complex, benchmarking can provide crucial insights.

In this talk, we’ll share our approach to benchmarking dynamically generated DAGs with Astronomer Cosmos (https://github.com/astronomer/astronomer-cosmos), covering:
* Designing representative and extensible baseline tests.
* Setting up an isolated, distributed infrastructure for benchmarking.
* Running reproducible performance tests.
* Measuring DAG run times and task throughput.
* Evaluating CPU & memory consumption to optimize deployments.

By the end of this session, you will have practical benchmarks and strategies for making informed decisions about evaluating the performance of DAGs in Airflow.