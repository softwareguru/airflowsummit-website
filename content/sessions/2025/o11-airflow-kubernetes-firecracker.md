---
title: "Airflow on Kubernetes & Firecracker: From Chaos to Clarity with Observability"
slug: airflow-kubernetes-firecracker
speakers:
 - Prerit Munjal

topics:
 - Airflow & ...
time_start: 2025-10-16 15:00:00
time_end: 2025-10-16 15:30:00
room: Online
track: Airflow & ...
day: 20255
timeslot: 11
gridarea: 3/2/4/3
images: 

slides:
video:
---

Four months ago, our Airflow environment was a black box. DAGs would fail silently, resource contention caused random task failures, and our data engineers were bypassing Airflow entirely because they couldn't trust it. Our solution? Rebuild Airflow as an observable, self-scaling platform on Kubernetes and Firecracker.

This talk dissects our transformation from Airflow uncertainty to operational confidence. I'll walk through how we instrumented our entire Airflow stack to provide real-time visibility into workflow execution, built a dynamic scaling system that handles our 5-10x daily traffic spikes, and implemented ephemeral environments(offering true isolation) that cut development cycles by 70%. We'll explore the exact architecture behind our ""Airflow Observatory"" – a monitoring system that tracks task execution across thousands of DAGs and predicts failures before they happen. Closing the session with a live demo of intelligent autoscaling and how we implemented custom sensors that dramatically improved pipeline reliability.