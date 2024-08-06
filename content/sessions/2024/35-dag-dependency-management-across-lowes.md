---
title: "DAG Dependency Management across Lowes"
slug: dag-dependency-management-across-lowes
speakers:
 - Arnab Kundu
time_start: 2024-09-10 17:10:00
time_end: 2024-09-10 17:35:00
room: California East
track: Use cases
day: 20241
timeslot: 35
gridarea: "14/2/15/3"
images: 
 - 
---

DAG dependency is already a solved use case for the same Airflow instance. But what happens when you have 50+ Airflow instances across teams and the workflow of one or many depends on others? By leveraging sensors and datasets we have created a custom operator that brings in the capability of cross-cluster dependencies. It works with our OnPrem Kubernetes architecture which is responsible for deployment of the custom operators throughout the entire Organization.