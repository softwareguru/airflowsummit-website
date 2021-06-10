---
id: b4
title: "Event-based Scheduling Based on Airflow"
url: /sessions/2021/event-based-scheduling
speakers:
 - Wuchao Chen
time_start: 2021-07-13T05:30:00.000Z
time_end: 2021-07-13T05:55:00.000Z
block: b
slot: 4
format: presentation
---

Airflow scheduler uses DAG definitions to monitor the state of tasks in the metadata database, and triggers the task instances whose dependencies have been met. It is based on state of dependencies scheduling. 
 The idea of event based scheduling is to let the operators send events to the scheduler to trigger a scheduling action, such as starting jobs, stopping jobs and restarting jobs. Event based scheduling allows potential support for richer scheduling semantics such as periodic execution and manual trigger at per operator granularity.