---
title: "Linkedin's Continuous Deployment"
slug: linkedin-s-continuous-deployment
speakers:
 - Rahul Gade
 - Keshav Tyagi
track:
 - Use cases
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

LinkedIn Continuous Deployment (LCD), started with the goal of improving the deployment experience and expanding its outreach to all LinkedIn systems. LCD delivers a modern deployment UX  and easy-to-customize pipelines which enables all LinkedIn applications to declare their deployment pipelines.

LCD's vision is to automate cluster provisioning, deployments and enable touchless (continuous) deployments while reducing the manual toil involved in deployments.

LCD is powered by Airflow to orchestrate its deployment pipelines and automate the validation steps. For our customers Airflow is an implementation detail and we have well abstracted it out with our no-code/low code pipelines. Users describe their pipeline intent (via CLI/UI) and LCD translates the pipeline intent into Airflow DAGs. 

LCD pipelines are built of steps. Inorder to democratize the adoption of the LCD, we have leveraged K8sPodOperator to run steps inside the pipeline. LCD partner teams expose validation actions as containers, which LCD pipeline runs as steps.  

At full scale, LCD will have about 10K+ DAGs running in parallel.