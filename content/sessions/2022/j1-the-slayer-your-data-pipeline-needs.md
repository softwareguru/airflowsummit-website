---
id: j1
title: "The SLAyer your Data Pipeline Needs"
url: /sessions/2022/the-slayer-your-data-pipeline-needs
speakers:
 - Eden Gluska
time_start: 2022-05-26T15:00:00.000Z
time_end: 2022-05-26T15:25:00.000Z
session_type: "Presentation"
hosted_by: "Tel Aviv"
presence: "onsite"
block: j
slot: 1
---

Airflow has an inherent SLA alert mechanism. When the scheduler sees such an SLA miss for some task, it sends an alert by email. The problem is, that this email is nice, but we can’t really know when each task is eventually successful. Moreover, even if there is such an email upon success following an SLA miss, it does not give us a good view of the current status at any given time.
 
In order to solve this, we developed SLAyer, an application that gets information of SLA misses from Airflow’s database and reports the current status to Prometheus, provides metrics per dag, task, and execution date currently in violation of its SLA.