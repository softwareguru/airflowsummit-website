---
title: "Implementing Airflow Governance with Cluster Policies"
slug: implementing-airflow-governance
speakers:
 - Karen Braganza
topics:
 - Best practices

track: Best practices
time_start: 2025-10-07 16:45:00
time_end: 2025-10-07 17:10:00
room: Columbia D
day: 20251
timeslot: 36
gridarea: 13/4/14/5 

slides:
video: 
images:
summary: "In this talk, Karen will take a more scenario-based approach, and talk about how cluster policies can be used to do things like prevent a Data Engineer from inserting/deleting data from a production database, or make sure that Tasks are always assigned to the right sized worker."
---

Governance in Airflow can be tricky; luckily, there are a couple of handy tools that Airflow provides to make this easier. Cluster policies provide teams using Airflow the ability to not only validate the DAGs and Tasks they've written but also mutate them. 

In this talk, Karen will take a more scenario-based approach, and talk about how cluster policies can be used to do things like prevent a Data Engineer from inserting/deleting data from a production database, or make sure that Tasks are always assigned to the right sized worker.