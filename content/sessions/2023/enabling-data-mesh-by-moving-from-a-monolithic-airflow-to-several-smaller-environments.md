---
title: "Enabling Data Mesh by Moving from a Monolithic Airflow to Several Smaller Environments"
slug: enabling-data-mesh-by-moving-from-a-monolithic-airflow-to-several-smaller-environments
speakers:
 - Filip Kunčar
 - Stanislav Repka
time_start: 2023-09-20T12:30:00-04:00
time_end: 2023-09-20T13:00:00-04:00
room: Ballroom A-B
track: Operationalizing Airflow
day: 2
timeslot: 7
---

Kiwi.com started using Airflow in June 2016 as an orchestrator for several people in the company. The need for the tool grew and the monolithic instance was used by 30+ teams having 500+ DAGs active resulting in 3.5 million tasks/month successfully finished.
 
 At first, we moved to using a monolithic Airflow environment, but our needs quickly changed as we wanted to support a data mesh architecture within kiwi.com. 
 
 By leveraging Astronomer on GCP, we were able to move from a monolithic Airflow environment to many smaller instances of Airflow. 
 
 This talk will go into how to handle things like DAG dependencies, observability, and stakeholder management. Furthermore, we’ll talk about security, particularly how GCP’s workload identity helped us achieve a passwordless Airflow experience.