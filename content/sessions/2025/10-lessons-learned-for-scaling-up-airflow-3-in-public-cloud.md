---
title: "Lessons learned for scaling up Airflow 3 in Public Cloud"
slug: lessons-learned-for-scaling-up-airflow-3-in-public-cloud
speakers:
 - Przemek Wiech
 - Augusto Hidalgo
topics:
 - Airflow 3
time_start: 2025-10-07 12:15:00
time_end: 2025-10-07 12:55:00
room: Columbia D
track: Airflow 3
day: 20251
timeslot: 10
gridarea: 5/4/6/5
images: 
 - /images/sessions/2025/lessons-learned-for-scaling-up-airflow-3-1.png
slides:
video: https://youtu.be/vfmpJnsV4Qk
summary: "This talk shares performance results for various Airflow 3 configurations and provides potential Airflow 3 adopters good understanding of its performance."
---

Apache Airflow 3 is a new state-of-the-art version of Airflow. For many users who plan to adopt Airflow 3 it's important to understand how Airflow 3 behaves from performance perspective compared to Airflow 2.

This presentation is going to present performance results for various Airflow 3 configurations and provides potential Airflow 3 adopters good understanding of its performance.

The reference Airflow 3 configuration will be using Kubernetes cluster as a compute layer, PostgreSQL as Airflow Database and would be performed on Google Cloud Platform. Performance tests will be performed using community version of performance tests framework and there might be references to Cloud Composer (managed service for Apache Airflow). The tests will be done in production-grade configurations that might be good references for Airflow community users. 

 - Users will be provided with comparison of Airflow 3 and Airflow 2 from performance standpoint 
 - Users also will learn how to optimize Airflow scheduler performance by understanding DAG file processing, task scheduling and configuring Scheduler to run tens of thousands of DAGs/tasks in Airflow 3