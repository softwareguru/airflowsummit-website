---
title: "Task failures troubleshooting based on Airflow & Kubernetes signals"
slug: task-failures-troubleshooting-based-on-airflow-kubernetes-signals
speakers:
 - Khadija Al Ahyane
topics:
 - Airflow & ...
time_start: 2025-10-09 14:00:00
time_end: 2025-10-09 14:25:00
room: Beckler
track: Airflow & ...
day: 20253
timeslot: 154
gridarea: 10/5/11/6
slides:
video: https://youtu.be/bzbXC4DtflQ
images:
 - /images/sessions/2025/task-failures-troubleshooting-based-on-airflow-kubernetes-signals.png
---

Per Airflow community survey, Kubernetes is the most popular compute platform used to run Airflow and when run on Kubernetes, Airflow gains, out of the box, lots of benefits like monitoring, reliability, ease of deployment, scalability and autoscaling. On the other hand, running Airflow on Kubernetes means running a sophisticated distributed system on another distributed system which makes troubleshooting of Airflow tasks and DAGs failures harder. 

This session tackles that bottleneck head-on, introducing a practical approach to building an automated diagnostic pipeline for Airflow on Kubernetes. Imagine offloading tedious investigations to a system that, on task failure, automatically collects and correlates key signals from Kubernetes components (linking Airflow tasks to specific Pods and their events), KubernetesGKE monitoring, and relevant logs—pinpointing root causes and suggesting actionable fixes.

Attendees will leave with a clear understanding of common Airflow-on-Kubernetes failure patterns—and more importantly, a blueprint and practical strategies to reduce MTTR and boost team efficiency.
