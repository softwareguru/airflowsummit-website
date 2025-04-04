---
title: "Airflow at StyleSeat: Our journey, challenges & results"
slug: airflow-at-styleseat-our-journey-challenges-results
aliases:
 - /sessions/2023/migration-to-airflow-our-journey-challenges-success
speakers:
 - Kunal Haria
 - Ramya Pappu
time_start: 2023-09-19T17:45:00-04:00
time_end: 2023-09-19T18:10:00-04:00
room: Ballroom C-D
track: Use cases
day: 1
timeslot: 17
images:
 - /images/sessions/2023/Kunal+Ramya.jpg
video: https://youtu.be/75z41Do-NaQ
slides: 2023/1-CD-1745-Airflow-at-StyleSeat.pdf
---

We will share the case study of Airflow at StyleSeat, where within a year our data grew from 2 million data points per day to 200 million. Our original solution for orchestrating this data was not enough, so we migrated to an Airflow based solution.
 
Previous implementation 
Our tasks were orchestrated with hourly triggers on AWS Cloudwatch rules in their own log groups. Each task was a lambda individually defined as a task and executed python code from a docker image. As complexity increased, there were frequent downtimes and manual executions for failed tasks and their downstream dependencies.With every downtime, our business stakeholders started losing trust in Data and recovery times were longer with each downtime.  
 
We needed a modern orchestration platform which would enable our team to define and instrument complex pipelines as code, provide visibility into executions and define retry criteria on failures.
 
Airflow was identified as a crucial & critical piece in modernizing our orchestration which would help us further onboard DBT. We wanted a managed solution and a partner who could help guide us to a successful migration.