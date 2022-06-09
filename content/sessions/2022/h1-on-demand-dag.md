---
id: h1
title: On-Demand DAG through the REST API
url: /sessions/2022/on-demand-dag
speakers:
 - Mocheng Guo
time_start: 2022-05-25T20:00:00.000Z
time_end: 2022-05-25T20:50:00.000Z
session_type: "Presentation"
hosted_by: bay
presence: onsite
block: h
slot: 1
video: https://youtu.be/5Ap2t9qJE18
slides: 
---

In this talk we want to present how Airbnb extends the REST api to support on-demand workload. A DAG object is created from a local environment like Jupyter notebook, serialized into binary and transported to the API. The API persists the DAG object into the meta DB and Airflow scheduler and worker are extended to process this new kind of DAG.