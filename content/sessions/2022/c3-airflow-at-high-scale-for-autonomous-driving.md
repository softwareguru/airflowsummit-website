---
id: c3
title: "Airflow at high scale for Autonomous Driving"
url: /sessions/2022/airflow-at-high-scale-for-autonomous-driving
speakers:
 - Philipp Lang
 - Anton Ivanov
time_start: 2022-05-23T05:00:00.000Z
time_end: 2022-05-23T05:40:00.000Z
format: "Presentation"
hosted_by: "Tokyo"
presence: "remote"
block: c
slot: 3
---

This talk highlights a large-scale use case of Airflow to orchestrate workflows for an Autonomous Driving project based in Germany.
 
 
 
 To support our customer in the aim of producing their first Level-3 Autonomous Driving vehicle in Germany, we are utilising Airflow as a state-of-the-art tool to orchestrate workloads running on a large-scale HPC platform. 
 
 In this talk, we will describe our Airflow setup deployed on OpenShift that is capable of running thousands of tasks in parallel and contains various custom improvements optimised for our use case. We will in detail discuss how we achieved to integrate multiple components with airflow such as a PostgreSQL database, a highly available RabbitMQ message broker and a fully integrated IAM solution. In particular, we will describe bottlenecks which we have encountered in our journey towards scaling up airflow, and how we mitigate them. We will also detail on the custom improvements we implemented on both airflow code base and deployment setup, such as an enhanced airflow logging framework, improvements on the Spark submit operator, and a feature to re-deploy airflow without business downtime. 
 
 
 
 The talk will be concluded with an outlook on future improvements that we anticipate, as well as beneficial features we believe will be helpful for the community.