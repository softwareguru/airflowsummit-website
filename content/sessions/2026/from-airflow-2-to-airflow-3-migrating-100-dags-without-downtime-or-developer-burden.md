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

When I took on the task of upgrading our Airflow's deployments from version 2 to 3, I knew the team couldn't afford a big-bang cutover or weeks of changes requested across different teams. Instead, we developed and shipped a compatibility layer before touching any infrastructure so by the time we flipped the version, everything already worked. 

In my talk, I would walk through how we built a Python shim that makes AF3 code run on AF2 during the migration, a custom connection backend that normalizes legacy connections at runtime and how we used AI-tooling to orchestrate and test 400+ DAG changes. I'd also share how our on-demand ephemeral environments - full k8s deployments that can be spun up on any Pull Request - helped us make sure that DAGs are properly processed, and that major changes to operators and jinja variables are validated in isolation. 

Most important of all, I would like to share what we learned, where we failed and what we would do better next time. 