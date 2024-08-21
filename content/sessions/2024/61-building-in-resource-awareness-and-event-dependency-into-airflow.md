---
title: "Building in Resource Awareness and Event Dependency into Airflow"
slug: building-in-resource-awareness-and-event-dependency-into-airflow
speakers:
 - Roberto Santamaria
 - Xiaodong Deng
 - Anandhi Murali
time_start: 2024-09-11 14:30:00
time_end: 2024-09-11 14:55:00
room: California West
track: Airflow & ...
day: 20242
timeslot: 61
gridarea: "11/3/12/4"
images: 
 - /images/sessions/2024/building-awareness.jpg
---

In this talk, we will explore how adding custom dependency checks into Airflow’s scheduling system can elevate Airflow’s performance. 
 
We will specifically discuss how we added general upstream events dependency checking as well as how to make Airflow aware of used/available compute resources so that the system can better decide when and where to run a given task on Kubernetes infrastructure.
 
We’ll cover why the existing dependency checking in Airflow is not sufficient in our use case, and why adding custom code to Airflow is needed. We’ll cover the pros and cons with this approach.