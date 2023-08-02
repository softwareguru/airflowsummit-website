---
title: "To Debug a DAG: The Airflow local dev story"
slug: to-debug-a-dag-the-airflow-local-dev-story
speakers:
 - Daniel Imberman
time_start: 2023-09-19T16:45:00-04:00
time_end: 2023-09-19T17:10:00-04:00
room: York
track: Airflow basics
day: 1
timeslot: 15
images:
 - /images/sessions/2023/DanielImberman.jpg

---

As much as we love airflow, local development has been a bit of a white whale through much of its history. Until recently, Airflow’s local development experience has been hindered by the need to spin up a scheduler and webserver. In this talk, we will explore the latest innovation in Airflow local development, namely the "dag.test()" functionality introduced in Airflow 2.5.
 
 
 
 We will delve into practical applications of "dag.test()", which empowers users to locally run and debug Airflow DAGs on a single python process. This new functionality significantly improves the development experience, enabling faster iteration and deployment.
 
 
 
 In this presentation, we will discuss:
 
 
 
 * How to leverage IDE support for code completion, linting, and debugging;
 
 * Techniques for inspecting and debugging DAG output,
 
 * Best practices for unit testing DAGs and their underlying functions.
 
 
 
 Accessible to Airflow users of all levels, join us as we explore the future of Airflow local development!