---
title: "Circumventing Airflows Limitations around Multitenancy"
slug: circumventing-airflows-limitations-around-multitenancy
speakers:
 - Anthony Kalsatos
 - Akshay Battaje
time_start: 2023-09-20T12:00:00-04:00
time_end: 2023-09-20T12:30:00-04:00
track: Operationalizing Airflow
---

A steady rise in users and business critical workflows poses challenges to development and production workflows. The solution: enable multi-tenancy on our single Airflow instance. We needed to enable teams to manage their python requirements, and ensure DAGs were insulated from each other. To achieve this we divided our monolithic setup into three parts: Infrastructure (with common code packaging), Workspace Creation, and CI/CD to manage deployments.
 
 
 
 Backstage templates enable teams to create isolated development environments that resemble our production environment, ensuring consistency. Distributing common code via a private pypi gives teams more control over what code their DAGs run. And a PythonOperator Shim in production utilizes virtualenv to run Python code with each team's defined requirements for their DAG. In doing these things we enable effective multi-tenancy, and facilitate easier development and production workflows for Airflow.