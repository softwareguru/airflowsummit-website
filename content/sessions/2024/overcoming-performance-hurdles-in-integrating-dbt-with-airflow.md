---
title: "Overcoming performance hurdles in Integrating dbt with Airflow"
slug: overcoming-performance-hurdles-in-integrating-dbt-with-airflow
speakers:
 - Tatiana Al-Chueyr Martins
 - Pankaj Koti
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

The integration between dbt and Airflow is a popular topic in the community, both in previous editions of Airflow Summit, in Coalesce and the #airflow-dbt Slack channel.

Astronomer Cosmos (https://github.com/astronomer/astronomer-cosmos/) stands out as one of the libraries that strives to enhance this integration,  having over 300k downloads per month. 

During its development, we've encountered various performance challenges in terms of scheduling and task execution. While we've managed to address some, others remain to be resolved.

This talk describes how Cosmos works, the improvements made over the last 1.5 years, and the roadmap. It also aims to collect feedback from the community on how we can further improve the experience of running dbt in Airflow.