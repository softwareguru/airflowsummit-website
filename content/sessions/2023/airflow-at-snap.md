---
title: "Airflow at Snap"
slug: airflow-at-snap
speakers:
 - Zhengyi Liu
 - Yuri Desyatnik
 - Han Gan
 - Nanxi Chen
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Operationalizing Airflow
---

We will cover how Snap (parent company of Snapchat) has been using Airflow since 2016. 

- How we built a secure deployment on GCP that integrates with internal tools for workload authorization, RBAC and more. We made permissions for DAGs easy to use for customers using k8s workload identity binding and tight UI integration. 

- How are we migrating 2500+ DAGs from Airflow V1, Python 2 to V2 Python 3 using tools + automations. Making code/DAG migration requires significant amount of time investment. Our team created several tools that can convert or re-write DAGs in the new format.

- Some other self-serving tools that we built internally.