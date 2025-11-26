---
title: "How Airflow solves the coordination of decentralised teams at Vinted"
slug: how-airflow-solves-the-coordination-of-decentralised-teams-vinted
speakers:
 - Oscar Ligthart
 - Rodrigo Loredo
topics:
 - Use cases
time_start: 2025-10-08 16:15:00
time_end: 2025-10-08 16:40:00
room: Columbia A
track: Use cases
day: 20252
timeslot: 98
gridarea: 14/2/15/3
slides: 2025/how-airflow-solves-the-coordination-of-decentralised-teams-@vinted.pdf
video: https://youtu.be/YU-4My_dneM
images:
 - /images/sessions/2025/how-airflow-solves.png
---

Vinted is the biggest second-hand marketplace in Europe with multiple business verticals. Our data ecosystem has over 20 decentralized teams responsible for generating, transforming, and building Data Products from petabytes of data. This creates a daring environment where inter-team dependencies, varied expertise with scheduling tools, and diverse use cases need to be managed efficiently. To tackle these challenges, we have centralized our approach by leveraging Apache Airflow to orchestrate data dependencies across teams.

In this session, we will present how we utilize a code generator to streamline the creation of Airflow code for numerous dbt repositories, dockerized jobs, and Vertex-AI pipelines. With this approach, we simplify the complexity and offer our users the flexibility required to accommodate their use cases. We will share our sensor-callback strategy, which we developed to manage task dependencies, overcoming the limitations of traditional dataset triggers. This approach requires a data asset registry to monitor global dependencies and SLOs, and serves as a safeguard during CI processes for detecting potential breaking changes.