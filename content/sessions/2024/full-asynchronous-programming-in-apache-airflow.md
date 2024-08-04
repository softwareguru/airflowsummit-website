---
title: "Full asynchronous programming in Apache Airflow"
slug: full-asynchronous-programming-in-apache-airflow
speakers:
 - Hussein Awala
track:
 - New features
images:
 - /images/sessions/2024/full-asynchronous.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
draft: true
---

Airflow uses multithreading in different components to parallelize the processing but relies heavily on synchronous execution, even for I/O blocking statements, which can slow down processing and increase resource usage.

In this session, I'll demonstrate how migrating Airflow's components—such as the web server, REST API, executors, and scheduler—to asynchronous programming can significantly reduce execution time, making Airflow faster and more efficient than ever.