---
title: "Airflow Executors: Past, present and future"
slug: airflow-executors-past-present-and-future
speakers:
 - Niko Oliveira
time_start: 2023-09-19T12:00:00-04:00
time_end: 2023-09-19T12:30:00-04:00
day: 1
timeslot: 6
room: Ballroom 1
track: New features/roadmap
---

Executors are a core concept in Apache Airflow and are an essential piece to the execution of DAGs. They have seen a lot of investment over the year and there are many exciting advancements that will benefit both users and contributors.
 
This talk will briefly discuss executors, how they work and what they are responsible for. It will then describe Executor Decoupling (AIP-51) and how this has fully unlocked development of third-party executors. We’ll touch on the migration of “core” executors (such as Celery and Kubernetes) to their own package as well as the addition of new “3rd party” executors from providers such as AWS. Finally, a description/demo of Hybrid Executors, a proposed new feature to allow multiple executors to be used natively and seamlessly side by side within a single Airflow environment; which will be a powerful feature in a future full of many new Airflow executors.