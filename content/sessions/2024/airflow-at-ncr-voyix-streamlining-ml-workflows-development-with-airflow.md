---
title: "Airflow at NCR Voyix: Streamlining ML workflows development with Airflow"
slug: airflow-at-ncr-voyix-streamlining-ml-workflows-development-with-airflow
speakers:
 - Shahar Epstein
track:
 - Use cases
images:
 - /images/sessions/2024/ncr.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

NCR Voyix Retail Analytics AI team offers ML products for retailers while embracing Airflow as its MLOps Platform. As the team is small and there have been twice as many data scientists as engineers, we encountered challenges in making Airflow accessible to the scientists:
1. As they come from diverse programming backgrounds, we needed an architecture enabling them to develop production-ready ML workflows without prior knowledge of Airflow.
2. Due to dynamic product demands, we had to implement a mechanism to interchange Airflow operators effortlessly.
3. As workflows serve multiple customers, they should be easily configurable and simultaneously deployable.
We came up with the following architecture to deal with the above:
1. Enabling our data scientists to formulate ML workflows as structured Python files.
2. Seamlessly converting the workflows into Airflow DAGs while aggregating their steps to be executed on different Airflow operators.
3. Deploying DAGs via CI/CD's UI to the DAGs folder for all customers while considering definitions for each in their configuration files.
In this session, we will cover Airflow’s evolution in our team and review the concepts of our architecture.