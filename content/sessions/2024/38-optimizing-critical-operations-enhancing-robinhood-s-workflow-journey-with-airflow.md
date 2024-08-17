---
title: "Optimizing Critical Operations: Enhancing Robinhood's Workflow Journey with Airflow"
slug: optimizing-critical-operations-enhancing-robinhood-s-workflow-journey-with-airflow
speakers:
 - Kevin Wang
 - Palanieppan Muthiah
 - Peiqiu Tian
time_start: 2024-09-10 17:10:00
time_end: 2024-09-10 17:35:00
room: Georgian
track: Use cases
day: 20241
timeslot: 38
gridarea: "14/5/15/6"
images: 
 - /images/sessions/2024/robinhood.jpg
---

Airflow is widely used within Robinhood. In addition to traditional offline analytics use cases (to schedule ingestion and analytics workloads that populate our data lake), we also use Airflow in our backend services to orchestrate various workflows that are highly critical for the business, e.g: compliance and regulatory reporting, user facing reports and more.
 
As part of this, we have evolved what we believe is a unique deployment architecture for Airflow. We have central schedulers that are responsible for workloads from multiple different teams, but the workflow tasks themselves run on workers owned by respective teams that are highly coupled with their backend services and codebase. 
 
Furthermore, Robinhood augmented Airflow with a bunch of customizations — airflow worker template for Kubernetes, enhanced observability, enhanced SLA detection, and a collection of operators, sensors, and plugins to tailor Airflow to their exact needs.
 
This session is going to walk through how we grew our architecture and adapted Airflow to fit Robinhood's variety of needs and use cases.