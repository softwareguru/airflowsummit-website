---
title: "Building in resource awareness and event dependency into Airflow"
slug: building-in-resource-awareness-and-event-dependency-into-airflow
speakers:
 - Roberto Santamaria
 - Xiaodong Deng
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

In this talk, we will explore how adding custom dependency checks into Airflow’s scheduling system can elevate Airflow’s  performance. 

We will specifically discuss how we added general upstream events dependency checking as well as how to make Airflow aware of used/available compute resources so that the system can better decide when and where to run a given task on Kubernetes infrastructure.

We’ll cover why the existing dependency checking in Airflow is not sufficient in our use case, and why adding custom code to Airflow  is needed.  We’ll cover the pros and cons with this approach.