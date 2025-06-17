---
title: "No More Missed Beats: How Airflow Rescued Our Analytics Pipeline"
slug: no-more-missed-beats-how-airflow-rescued-our-analytics-pipeline
speakers:
 - pei-chi-miko-chen
topics:
 - Use cases
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Before Airflow, our BigQuery pipelines at Create Music Group operated like musicians without a conductor—each playing on its own schedule, regardless of whether upstream data was ready. As our data platform grew, this chaos led to spiralling costs, performance bottlenecks, and became utterly unsustainable.

This talk tells the story of how Create Music Group brought harmony to its data workflows by adopting Apache Airflow and the Medallion architecture, ultimately slashing our data processing costs by 50%. We’ll show how moving to event-driven scheduling with datasets helped eliminate stale data issues, dramatically improved performance, and unlocked faster iteration across teams. Discover how we replaced repetitive SQL with standardized dimension/fact tables, empowering analysts in a safer sandbox.