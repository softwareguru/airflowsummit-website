---
id: 
title: "The SLAyer your Data Pipeline Needs"
url: /sessions/2022/the-slayer-your-data-pipeline-needs
speakers:
 - Eden Gluska
block: 
slot: 
track: Airflow internals
time_start: 2022-01-01T17:00:00.000Z
time_end: 2022-01-01T18:00:00.000Z

---

Airflow has an inherent SLA alert mechanism. When the scheduler sees such an SLA miss for some task, it sends an alert by email. The problem is, that this email is nice, but we can’t really know when each task is eventually successful. Moreover, even if there is such an email upon success following an SLA miss, it does not give us a good view of the current status at any given time.
 
 
 
 In order to solve this, we developed SLAyer, an application that gets information of SLA misses from Airflow’s database and reports the current status to Prometheus, provides metrics per dag, task, and execution date currently in violation of its SLA.