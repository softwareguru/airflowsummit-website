---
title: "Boosting dbt-core workflows performance with Airflow’s Deferrable capabilities"
slug: boosting-dbt-core-workflows-performance-with-airflows-deferrable-capabilities
speakers:
 - Pankaj Koti
 - Tatiana Al-Chueyr Martins
 - Pankaj Singh
topics:
 - Airflow & ...
time_start: 2025-10-08 12:00:00
time_end: 2025-10-08 12:25:00
room: Columbia A
track: Airflow & ...
day: 20252
timeslot: 56
gridarea: 6/3/7/4
slides:
video:
---

Efficiently handling long-running workflows is crucial for scaling modern data pipelines. Apache Airflow’s deferrable operators help offload tasks during idle periods — freeing worker slots while tracking progress.

This session explores how Cosmos 1.9 (https://github.com/astronomer/astronomer-cosmos)  integrates Airflow’s deferrable capabilities to enhance orchestrating dbt (https://github.com/dbt-labs/dbt-core)  in production, with insights from recent contributions that introduced this functionality.

Key takeaways:
 * Deferrable Operators: How they work and why they’re ideal for long-running dbt tasks.
 * Integrating with Cosmos: Refactoring and enhancements to enable deferrable behaviour across platforms.
 * Performance Gains: Resource savings and task throughput improvements from deferrable execution.
 * Challenges & Future Enhancements: Lessons learned, compatibility, and ideas for broader support.

Whether orchestrating dbt models on a cloud warehouse or managing large-scale transformations, this session offers practical strategies to reduce resource contention and boost pipeline performance.