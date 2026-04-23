---
title: "From Airflow 2 to Airflow 3: Migrating 100+ DAGs Without Downtime or Developer Burden"
slug: from-airflow-2-to-airflow-3-migrating-100-dags-without-downtime-or-developer-burden
speakers:
 - Goncalo Costa
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Migrating a production Airflow deployment from version 2 to 3 without disrupting hundreds of DAGs across multiple teams sounds scary (and it is). In this talk I will share how we migrated versions without a big-bang cutover, without weeks of cross-team change requests, and without leaving our pipelines in a broken state. 

I’ll walk through how we built a compatibility layer to make sure our code runs on both versions during the migration, how we used AI-tooling to orchestrate 400+ DAG changes and how our on-demand ephemeral environments - full k8s deployments deployed for each pull request - helped us experiment and test all the required changes. 

Most important of all, I will share what we learned, where we failed and what we would do better next time.