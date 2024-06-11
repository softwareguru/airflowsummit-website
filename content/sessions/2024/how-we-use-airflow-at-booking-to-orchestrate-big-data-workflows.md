---
title: "How we use Airflow at Booking to orchestrate Big Data workflows"
slug: how-we-use-airflow-at-booking-to-orchestrate-big-data-workflows
speakers:
 - Madhav Khakhar
 - Alexander Shmidt
track:
 - Use cases
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

The talk will cover how we use Airflow at the heart of our Workflow Management Platform(WFM) at Booking.com, enabling our internal users to orchestrate big data workflows on Booking Data Exchange(BDX).

High level overview of the talk:
- Adapting open source Airflow helm chart to spin up Airflow installation in Booking Kubernetes Service (BKS)
- Coming up with Workflow definition format (yaml)
- Conversion of workflow.yaml to workflow.py DAGs
- Usage of Deferrable operators to provide standard step templates to users
- Workspaces (collection of workflows), using it to ensure role based access to DAG permissions for users
- Using okta for authentication
- Alerting, monitoring, logging
- Plans to shift to Astronomer