---
title: "Platform for Genomic Processing Using Airflow and ECS"
slug: platform-for-genomic-processing-using-airflow-and-ecs
speakers:
 - Zohar Donenhirsh
 - Alina Aven
time_start: 2023-09-20T15:30:00-04:00
time_end: 2023-09-20T15:55:00-04:00
room: Ballroom crush
track: Airflow & ...
day: 2
timeslot: 12
images:
 - /images/sessions/2023/Zohar+Alina.jpg
video: https://youtu.be/j4fmIh3ir3I
slides: 
---

High-scale orchestration of genomic algorithms using Airflow workflows, AWS Elastic Container Service (ECS), and Docker.

Genomic algorithms are highly demanding of CPU, RAM, and storage. Our data science team requires a platform to facilitate the development and validation of proprietary algorithms. The Data engineering team develops a research data platform that enables Data Scientists to publish docker images to AWS ECR and run them using Airflow DAGS that provision AWS's ECS compute power of EC2 and Fargate.

We will describe a research platform that allows our data science team to check their algorithms on ~1000 cases in parallel using airflow UI and dynamic DAG generation to utilize EC2 machines, auto-scaling groups, and ECS clusters across multiple AWS regions.