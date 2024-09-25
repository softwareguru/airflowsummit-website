---
title: "Linkedin's Continuous Deployment"
slug: linkedin-s-continuous-deployment
speakers:
 - Rahul Gade
 - Keshav Tyagi

time_start: 2024-09-11 11:30:00
time_end: 2024-09-11 12:15:00
room: California East
track: Use cases
day: 20242
timeslot: 49
gridarea: "6/2/8/3"

images: 
 - /images/sessions/2024/linkedin.jpg
slides: 2024/38-Linkedins-Continuous-Deployment.pdf
video: 
---

LinkedIn Continuous Deployment (LCD), started with the goal of improving the deployment experience and expanding its outreach to all LinkedIn systems. LCD delivers a modern deployment UX and easy-to-customize pipelines which enables all LinkedIn applications to declare their deployment pipelines.
 
 
 
 LCD's vision is to automate cluster provisioning, deployments and enable touchless (continuous) deployments while reducing the manual toil involved in deployments.
 
 
 
 LCD is powered by Airflow to orchestrate its deployment pipelines and automate the validation steps. For our customers Airflow is an implementation detail and we have well abstracted it out with our no-code/low code pipelines. Users describe their pipeline intent (via CLI/UI) and LCD translates the pipeline intent into Airflow DAGs. 
 
 
 
 LCD pipelines are built of steps. Inorder to democratize the adoption of the LCD, we have leveraged K8sPodOperator to run steps inside the pipeline. LCD partner teams expose validation actions as containers, which LCD pipeline runs as steps. 
 
 
 
 At full scale, LCD will have about 10K+ DAGs running in parallel.