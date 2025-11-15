---
title: "Security made us do it: Airflow’s new Task Execution Architecture"
slug: security-made-us-do-it-airflows-new-task-execution-architecture
speakers:
 - Amogh Desai
 - Ash Berlin-Taylor
topics:
 - Airflow 3
time_start: 2025-10-07 11:30:00
time_end: 2025-10-07 12:10:00
room: Columbia A
track: Airflow 3
day: 20251
timeslot: 4
gridarea: 4/2/5/3
images: 
 - /images/sessions/2025/security-made-us-do-it.png
slides:
video: https://youtu.be/ome8BUtD_n0
summary: "Join us to explore how AIP-72 transforms Airflow task execution, paving the way for a more secure, flexible, and futuristic task orchestration!"
---

Airflow v2 architecture has strong coupling between the Airflow core & the User Code running in an Airflow task. This poses barriers in security, maintenance, and adoption. One such threat is that user code can access the source of truth of Airflow - the metadata DB and run any query against it! From a scalability angle, ‘n’ tasks create ‘n’ DB connections, limiting Airflow’s ability to scale effectively.

To address this we proposed AIP-72 – a client-server model for task execution. The new architecture addresses several long-standing issues, including DB isolation from workers, dependency conflicts between Airflow core & workers, and ‘n’ number of DB connections.The new architecture has two parts:
1. Execution API Server: Tasks no longer have direct DB access, they use this new slim, secure API
2. Task SDK: A lightweight toolkit that lets you write tasks without drowning within Airflow's codebase

Beyond isolation and security, the redesign unlocks the ability for native multi-language task authoring support, and secure Remote Execution. Join us to explore how AIP-72 transforms Airflow task execution, paving the way for a more secure, flexible, and futuristic task orchestration!