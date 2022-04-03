---
id: 
title: "A look under the hood of the Airflow logging subsystem"
url: /sessions/2022/under-the-hood-of-the-airflow-logging-subsystem
speakers:
 - Philippe Gagnon
block: 
slot: 
track: Airflow internals
time_start: 2022-01-01T17:00:00.000Z
time_end: 2022-01-01T18:00:00.000Z

---

The task logging subsystem is one of most flexible, yet complex and misunderstood components of Airflow.

In this talk, we will take a look at the various task log handlers that are part of the core Airflow distribution, and dig a bit deeper in the interfaces they implement and discuss how those can be used to roll your own logging implementation.