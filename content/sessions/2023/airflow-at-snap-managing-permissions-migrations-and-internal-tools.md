---
title: "Airflow at Snap: Managing permissions, migrations and internal tools"
slug: airflow-at-snap-managing-permissions-migrations-and-internal-tools
aliases:
 - /sessions/2023/airflow-at-snap
speakers:
 - Zhengyi Liu
 - Yuri Desyatnik
 - Han Gan
 - Nanxi Chen
time_start: 2023-09-19T16:45:00-04:00
time_end: 2023-09-19T17:10:00-04:00
room: Ballroom C-D
track: Use cases
day: 1
timeslot: 15
images:
 - /images/sessions/2023/Zhengyi+Yuri+Han+Nanxi-Snap.jpg

---

We will cover how Snap (parent company of Snapchat) has been using Airflow since 2016. 
 
 - How we built a secure deployment on GCP that integrates with internal tools for workload authorization, RBAC and more. We made permissions for DAGs easy to use for customers using k8s workload identity binding and tight UI integration. 
 
 - How are we migrating 2500+ DAGs from Airflow V1, Python 2 to V2 Python 3 using tools + automations. Making code/DAG migration requires significant amount of time investment. Our team created several tools that can convert or re-write DAGs in the new format.
 
 - Some other self-serving tools that we built internally.