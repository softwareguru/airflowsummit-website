---
title: "Things to Consider When Building an Airflow Service"
slug: things-to-consider-when-building-an-airflow-service
speakers:
 - Viraj Parekh
 - Pete DeJoy
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
session_type: breakout
---

Data platform teams often find themselves in a situation where they have to provide Airflow as a service to downstream teams, as more users and use cases in their organization require an orchestrator. In these situations, it's giving each team it's own Airflow environment can unlock velocity and actually be lower overhead to maintain than a monolithic environment.



This talk will be about things to keep in mind when building an Airflow service that supports several environments, persona of users, and use cases. Namely, we'll discuss principles to keep in mind when balancing centralized control over the data platform with decentralized teams using Airflow in a way that they'll need. This will include things around observability, developer productivity, security, and infrastructure. We'll also talk about day 2 concerns around overheard, infrastructure maintenance, and other tradeoffs to consider. 