---
title: "Linkedin's journey on scaling Airflow"
slug: linkedin-s-journey-on-scaling-airflow
speakers:
 - Rahul Gade
 - Arun Kumar
topics:
 - Airflow & ...
time_start: 2025-10-07 11:30:00
time_end: 2025-10-07 12:10:00
images:
 - /images/sessions/2025/linkedins-journey-on-scaling-airflow.png
room: Columbia D
track: Airflow & ...
day: 20251
timeslot: 6
gridarea: 4/4/5/5
slides:
video: https://youtu.be/xFqKFcx74WQ
summary: "Following up from our session last year, we will take a deeper dive into the challenges, solutions, and engineering innovations that helped us scale Airflow to support thousands of concurrent tasks while maintaining usability and reliability."
---

Last year, we shared how LinkedIn's continuous deployment platform (LCD) leveraged Apache Airflow to streamline and automate deployment workflows. LCD is the deployment platform inside Linkedin which is actively used by all engineers (10000+) at Likedin.

This year, we take a deeper dive into the challenges, solutions, and engineering innovations that helped us scale Airflow to support thousands of concurrent tasks while maintaining usability and reliability.

Key Takeaways:
 * Abstracting Airflow for a Better User Experience – How we designed a system where users could define and update their workflows without directly interacting with Airflow.
 * Scaling to 10,000+ Concurrent Tasks – The architectural and configuration changes that enabled us to scale execution efficiently.
 * Enhanced Observability & Monitoring – The tools and techniques we implemented to track Airflow’s health, detect failures, and improve reliability.
 * Lessons from the Field – Key learnings, trade-offs, and best practices for managing large-scale Airflow deployments.

