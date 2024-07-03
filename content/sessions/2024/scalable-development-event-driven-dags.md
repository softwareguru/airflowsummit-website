---
title: "Scalable Development of Event Driven Airflow DAGs"
speakers:
 - Subramanian Vellaiyan
 - Ipsa Trivedi
track:
 - Use cases
time_start: 2021-07-18T16:00:00.000Z
time_end: 2021-07-18T16:45:00.000Z
draft: false
---

This usecase shows how we deal with data of different varieties from different sources. Each source sends data in different layout, timings, structures, location patterns sizes. The goal is to process the files within SLA and send them out. This a complex multi step processing pipeline that involves multiple spark jobs, api based integrations with microservices, resolving unique ids, deduplication and filtering. Note that this is an event driven system, but not a streaming data system. The files are of gigabyte scale, and each day the data being processed is of terabyte scale.

We will be talking about how to make DAG creation and business logic building a “low-code no-code process” so that non technical analysts can write business logic and light developers can deploy DAGs without much manual effort. Every aspect is either source specific or source-agnostic configuration driven.

Airflow was chosen to enable easy DAG building, scaling, monitoring, troubleshooting and rerunning.