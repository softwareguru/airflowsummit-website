---
title: "How we use Airflow at Booking to Orchestrate Big Data Workflows"
slug: how-we-use-airflow-at-booking-to-orchestrate-big-data-workflows
speakers:
 - Madhav Khakhar
 - Alexander Shmidt
 - Mayank Chopra
time_start: 2024-09-12 11:30:00
time_end: 2024-09-12 11:55:00
room: California East
track: Use cases
day: 20243
timeslot: 89
gridarea: "6/2/7/3"
images: 
 - /images/sessions/2024/booking.jpg
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