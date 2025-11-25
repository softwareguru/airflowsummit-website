---
title: "Using Apache Airflow with Trino for (almost) all your data problems"
slug: using-apache-airflow-with-trino-for-almost-all-your-data-problems
speakers:
 - Philippe Gagnon
topics:
 - Airflow & ...
time_start: 2025-10-09 12:00:00
time_end: 2025-10-09 12:25:00
room: Columbia C
track: Airflow & ...
day: 20253
timeslot: 137
gridarea: 7/3/8/4
slides:
video: https://youtu.be/NRbB3FuvVBg
---

Trino is incredibly effective at enabling users to extract insights quickly and effectively from large amount of data located in dispersed and heterogeneous federated data systems.

However, some business data problems are more complex than interactive analytics use cases, and are best broken down into a sequence of interdependent steps, a.k.a. a workflow. For these use cases, dedicated software is often required in order to schedule and manage these processes with a principled approach.

In this session, we will look at how we can leverage Apache Airflow to orchestrate Trino queries into complex workflows that solve practical batch processing problems, all the while avoiding the use of repetitive, redundant data movement.