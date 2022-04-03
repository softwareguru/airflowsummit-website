---
id: 
title: "Airflow extensions for governing a self-serviced data mesh"
url: /sessions/2022/airflow-extensions-governance
speakers:
 - Jorrick Sleijster

block: 
slot: 
track: Data governance
time_start: 2022-01-01T17:00:00.000Z
time_end: 2022-01-01T18:00:00.000Z

---

While many companies set up isolated data teams, Adyen is a strong believer of the data mesh approach, with all our data living in a central place. While our tooling teams provide and operate the on-premise cluster, the product teams are able to take full ownership of their data pipelines. 
 
Our 100+ users, spread across 10+ teams, own in total more than 200 dags and 4000 tasks. We use a single Airflow instance with many cross-dag and cross-stream dependencies within these 200 dags. As it’s impossible to keep track of all 4000 tasks as a single entity, these pipelines can only be managed by the teams themselves. 
 
In this presentation we will take a deep dive in how we structured DAG-level ACLs by using a governance library. Then, we continue by showcasing how we enabled our product teams to manage their tables with automated retention based removals, automated compaction, and table schema setup. Finally, we will showcase how making the teams able to manage the resources of their pipelines helped us iterate and saved us patching.