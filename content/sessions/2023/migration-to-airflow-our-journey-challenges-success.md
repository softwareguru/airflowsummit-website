---
title: "Migration to Airflow: Our journey, challenges & success"
slug: migration-to-airflow-our-journey-challenges-success
speakers:
 - Kunal Haria
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Use cases
---

Data plays an integral role in StyleSeats decision making process and our data grew from 2 million data points per day to 200 million within a year. The number of ETL tasks grew along with the growth of data and we struggled to track failures, monitor delays and manage retries.



Implementation

Our tasks were orchestrated with hourly triggers on AWS Cloudwatch rules in their own log groups. Each task was a lambda individually defined as a task and executed python code from a docker image. As complexity increased, there were frequent downtimes and manual executions for failed tasks and their downstream dependencies.



With every downtime, our business stakeholders started losing trust in Data and recovery times were longer with each downtime.



We needed a modern orchestration platform which would enable our team to define and instrument complex pipelines as code, provide visibility into executions and define retry criteria on failures



Airflow was identified as a crucial & critical piece in modernizing our orchestration which would help us further onboard DBT. We wanted a managed solution and a partner who could help guide us to a successful migration (edited) 