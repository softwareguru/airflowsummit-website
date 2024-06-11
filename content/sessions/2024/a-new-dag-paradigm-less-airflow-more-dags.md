---
title: "A New DAG Paradigm: Less Airflow more DAGs"
slug: a-new-dag-paradigm-less-airflow-more-dags
speakers:
 - Marion Azoulai
 - Maggie Stark
track:
 - Use cases
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Astronomer’s data team recently underwent a major shift in how we work with Airflow. We’ll deep dive into the challenges which prompted that change, how we addressed them and where we are now. 

This re-architecture included: 
Switching to dataset scheduling and micro-pipelines to minimize failures and increase reliability.
Implementing a Control DAG for complex dependency management and full end-to-end pipeline visibility.
Standardized Task Groups for quick onboarding and scalability.

With Airflow managing itself, we can once again focus on the data rather than the operational overhead. As proof we’ll share our favorite statistics from the terabyte of data we process daily revealing insights into how the world’s data teams use Airflow.