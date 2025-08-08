---
title: "Event-Driven Airflow 3.0: Real-Time Orchestration with Pub/Sub"
slug: event-driven-airflow-3-0-real-time-orchestration-with-pub-sub
speakers:
 - Andrea Bombino
 - Nawfel Bacha
topics:
 - Airflow 3
time_start: 2025-10-08 14:00:00
time_end: 2025-10-08 14:25:00
room: Columbia C
track: Airflow 3
day: 20252
timeslot: 70
gridarea: 9/3/10/4
slides:
video:
images:
 - /images/sessions/2025/event-driven.png
---

Traditional time-based scheduling in Airflow can lead to inefficiencies and delays. With Airflow 3.0, we can now leverage native event-driven DAG execution, enabling workflows to trigger instantly when data arrives—eliminating polling-based sensors and rigid schedules.
This talk explores real-time orchestration using Airflow 3.0 and Google Cloud Pub/Sub. We’ll showcase how to build an event-driven pipeline where DAGs automatically trigger as new data lands, ensuring faster and more efficient processing.
Through a live demo, we’ll demonstrate how Airflow listens to Pub/Sub messages and dynamically triggers dbt transformations only when fresh data is available. This approach improves scalability, reduces costs, and enhances orchestration efficiency.
Key Takeaways:  How event-driven DAGs work vs. traditional scheduling, Best practices for integrating Airflow with Pub/Sub,Eliminating polling-based sensors for efficiency,Live demo: Event-driven pipeline with Airflow 3.0, Pub/Sub & dbt.

This session will showcase how Airflow 3.0 enables truly real-time orchestration.