---
title: "Investigating the Many Loops of the Airflow Scheduler"
slug: investigating-the-many-loops-of-the-airflow-scheduler
speakers:
 - Philippe Gagnon
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

The scheduler is unarguably the most important component of an Airflow cluster. It is also the most complex and misunderstood by practitioners and administrators alike.

In this talk, we will follow the path that a task instance takes to progress from creation to execution, and discuss the various configuration settings allowing users to tune the scheduler and executor to suit their workload patterns. Finally, we will dive deep into critical sections of the Airflow codebase and explore opportunities for optimization.