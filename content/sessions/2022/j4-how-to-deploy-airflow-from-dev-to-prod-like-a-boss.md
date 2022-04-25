---
id: j4
title: "How to Deploy Airflow From Dev to Prod Like A BOSS"
url: /sessions/2022/how-to-deploy-airflow-from-dev-to-prod-like-a-boss
speakers:
 - Evgeny Shulman
time_start: 2022-05-26T03:00:00.000Z
time_end: 2022-05-26T03:20:00.000Z
format: "Presentation"
hosted_by: "Tel Aviv"
presence: "onsite"
block: j
slot: 4
---

Managing Airflow in large-scale environments is tough. You know this, and I know this. 
 
 
 
 But, what if you had a guide to make development, testing, and production lifecycles more manageable? 
 
 
 
 In this presentation, I will share how we manage Airflow for large-scale environments with friendly deployments at every step.
 
 
 
 After attending the session, Airflow engineers will:
 
 
 
 - Understand the advantages of each kind of deployment
 
 - Know the differences between Deployment and Airflow Executor
 
 - Deploy how to incorporate all kinds of deployments for their day-to-day needs
 
 
 
 
 
 
 
 
 
 ********************************************************************
 
 
 
 Detailed Description:
 
 
 
 - Airflow Deployment
 
  - Why it’s important
 
  - What’s wrong with saying “I use k8s at my Airflow cluster”. Airflow Executor vs Airflow Deployment
 
 - Deploying our Airflow Environments for multiple use cases:
 
  - Docker-compose - for fast, iterative development
 
  - Kubernetes with Helm Chart - for production
 
  - CI/CD
 
  - Local development tips and tricks
 
 - Our development cycle:
 
  - Starting with docker-compose
 
  - Moving to production with Helm + Kubernetes
 
  - How to incorporate Airflow, as a standard part of our development lifecycle including version management and other moving pieces.
 
 - Challenges we had to solve
 
  - DAGs deployment
 
  - Managing connections and variables
 
 - What are the options?
 
  - A short intro into helm and SAAS.
 
  - Managed Airflow.