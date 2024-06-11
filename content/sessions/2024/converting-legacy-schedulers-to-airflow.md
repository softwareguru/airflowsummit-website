---
title: "Converting Legacy Schedulers to Airflow"
slug: converting-legacy-schedulers-to-airflow
speakers:
 - Fritz Davenport
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Introducing a process and framework to convert legacy scheduler workloads such as Control-M to Airflow using automated transpilation techniques. We will discuss the process and demonstrate a python-based transpiler to automatically migrate legacy scheduler workflows with a standard set of patterns to Airflow DAGs. This framework is easily extended via configurable rulesets to encompass other schedulers such as Automic, Autosys, Oozie, and others.