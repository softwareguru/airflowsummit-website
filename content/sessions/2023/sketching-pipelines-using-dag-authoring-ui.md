---
title: "Sketching Pipelines Using DAG Authoring UI"
slug: sketching-pipelines-using-dag-authoring-ui
speakers:
 - Amogh Desai
 - Shubham Raj
time_start: 2023-09-20T16:15:00-04:00
time_end: 2023-09-20T16:40:00-04:00
room: Ballroom crush
track: Airflow & ...
day: 2
timeslot: 14
images:
 - /images/sessions/2023/Amogh+Shubham.jpg
video: https://youtu.be/gp1WYXfpwv0
slides: 
---

Cloudera Data Engineering (CDE) is a serverless service for Cloudera Data Platform that allows you to submit various Spark jobs and Airflow DAGs to an auto-scaling cluster.
 
Running your workloads as Python DAG files may be the usual, but not the most convenient way for some users as it involves a lot of background around syntaxes, the programming language, aesthetics of Airflow, etc. 
  
The DAG Authoring UI is a tool built on top of Airflow APIs to allow one to use a graphical user interface to create, manage, and destroy complex DAGs. The DAG authoring UI will give one the ability to perform tasks on Airflow without really having to know DAG structure, Python programming language, and the internals of Airflow. 
  
CDE has identified multiple operators to perform various tasks on Airflow by carefully categorising the use cases. The operators range from BashOperator, PythonOperator, CDEJobRunOperator, CDWJobRunOperator
 
Most use cases can be run as combinations of the operators provided.