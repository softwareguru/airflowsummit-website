---
title: "Reliable Airflow DAG Design When Building a Time-Series Data Lakehouse"
slug: reliable-airflow-dag-design-when-building-a-time-series-data-lakehouse
speakers:
 - Sung Yun
time_start: 2023-09-19T15:00:00-04:00
time_end: 2023-09-19T15:25:00-04:00
room: Ballroom C-D
track: Use cases
day: 1
timeslot: 11
images:
 - /images/sessions/2023/SungYun.jpg
video: https://youtu.be/DuztFxIo9Lo?si=yxFEaYnlKMXhyd-j
slides: 2023/1-CD-1500-Reliable-Airflow-DAG-Design.pdf
---

As a team that has built a Time-Series Data Lakehouse at Bloomberg, we looked for a workflow orchestration tool that could address our growing scheduling requirements. We needed a tool that was reliable and scalable, but also could alert on failures and delays to enable users to recover quickly from them. From using triggers over simple sensors to implementing custom SLA monitoring operators, we explore our choices in designing Airflow DAGs to create a reliable data delivery pipeline that is optimized for failure detection and remediation.