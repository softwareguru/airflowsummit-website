---
title: "Platform for genomic processing using Airflow and ECS"
slug: platform-for-genomic-processing-using-airflow-and-ecs
speakers:
 - Zohar Donenhirsh
 - Alina Aven
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Airflow & ...
session_type: breakout
---

High-scale orchestration of genomic algorithms using Airflow workflows, AWS elastic container service (ECS), and docker.

Genomic algorithms are highly demanding of CPU, RAM, and storage. Our data science team requires a platform to facilitate the development and improving proprietary algorithms. The Data engineering team develops a research data platform that enables Data Scientists to publish docker images to amazon ECR and run them using airflow dags that provision amazon's ECS compute power of EC2 and Fargate. 

We will describe a research platform that allows our data science team to check their algorithms on ~1000 cases in parallel using airflow UI and dynamic DAG generation to utilize EC2 machines, auto-scaling groups, and ECS clusters across multiple AWS regions.