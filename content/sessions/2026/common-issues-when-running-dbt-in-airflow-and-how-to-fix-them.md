---
title: "Common Issues When Running dbt in Airflow (and How to Fix Them)"
slug: common-issues-when-running-dbt-in-airflow-and-how-to-fix-them
speakers:
 - Tatiana Al-Chueyr Martins
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

In many modern data platforms, orchestration tools are combined with transformation frameworks. A common pattern is orchestrating dbt (data build tool) transformations using Apache Airflow — something reported by roughly 44% of the community.

At first glance, the integration seems straightforward: simply run dbt run inside an Airflow task. Some teams go further and use libraries that convert dbt projects into native Airflow DAGs, such as Astronomer Cosmos.

In practice, however, teams quickly run into operational and architectural challenges. Slowness, out-of-memory errors, zombie tasks, and DAGs that take minutes to appear in the UI are just a few of the issues that can emerge as projects scale.

In this talk, I’ll walk through the most common problems I’ve encountered while supporting organisations running dbt with Airflow, explain why they occur, and share practical strategies to avoid or resolve them. The goal is to help teams build more reliable and scalable pipelines when combining Airflow orchestration with dbt transformations.