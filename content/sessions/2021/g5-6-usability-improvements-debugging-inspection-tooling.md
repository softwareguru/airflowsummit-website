---
id: g5-6
title: "Usability Improvements: Debugging & Inspection Tooling"
url: /sessions/2021/usability-improvements-debugging-inspection-tooling
speakers:
 - Ace Haidrey
time_start: 2021-07-16T06:00:00.000Z
time_end: 2021-07-16T06:50:00.000Z
block: g
slot: 5-
---

The two most common user questions at Pinterest are: 1) why is my workflow running so long? 2) why did my workflow fail - is it my issue, or a platform issue?
 As with any big data organization, the workflow platform is just the orchestrator but the “real” work is done on another layer, managed by another platform. There can be plenty of these, and the challenges of figuring out the root cause of an issue can be mundane and time consuming. At Pinterest, we set out to provide additional tooling in our Airflow webserver to make it a quicker inspection process and provide smart tips such as increased runtime analysis, bottleneck identifying, rca, and an easy way for backfilling. We explore deeper the tooling provided to reduce the admin load, and empower our users.