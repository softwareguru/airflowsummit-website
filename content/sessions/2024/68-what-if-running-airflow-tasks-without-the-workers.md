---
title: "What If...? Running Airflow Tasks without the workers"
slug: what-if-running-airflow-tasks-without-the-workers
speakers:
 - Wei Lee
time_start: 2024-09-11 15:40:00
time_end: 2024-09-11 16:05:00
room: Elizabethan A+B
track: New features
day: 20242
timeslot: 68
gridarea: "13/4/14/5"
images: 
 - /images/sessions/2024/what-if.jpg
slides: 2024/60-what-if-running-airflow-tasks-without-the-workers.pdf
video: 
---

Airflow executes all tasks on the workers, including deferrable operators that must run on the workers before deferring to the triggerer. However, running some tasks directly from the triggerer can be beneficial in certain situations. This presentation will explain how deferrable operators function and examine ways to modify the Airflow implementation to enable tasks to run directly from the triggerer.