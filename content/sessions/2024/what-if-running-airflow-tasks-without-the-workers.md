---
title: "What If...? Running Airflow Tasks without the workers"
slug: what-if-running-airflow-tasks-without-the-workers
speakers:
 - Wei Lee
track:
 - New features
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Airflow executes all tasks on the workers, including deferrable operators that must run on the workers before deferring to the triggerer. However, running some tasks directly from the triggerer can be beneficial in certain situations. This presentation will explain how deferrable operators function and examine ways to modify the Airflow implementation to enable tasks to run directly from the triggerer.
