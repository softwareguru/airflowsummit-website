---
title: "Toward a Polyglot Airflow"
slug: toward-a-polyglot-airflow
speakers:
 - Tzu-ping Chung
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Building on Airflow 3’s new worker structure and foundation laied by Go SDK, we take a look at how Airflow can support a fully cross-language Dag-authoring experience.

We will discuss how a new language SDK is built, how a task talks to Airflow, and how multiple languages may be mixed inside a Dag. To support additional languages without logic duplication, a new middle layer is required between Airflow and the task. Additional topics, such as security, distributed workload, and user interface considerations, will also be touched on.