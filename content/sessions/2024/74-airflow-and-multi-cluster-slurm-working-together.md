---
title: "Airflow and multi-cluster Slurm working together"
slug: airflow-and-multi-cluster-slurm-working-together
speakers:
 - Eloi Codina Torras
time_start: 2024-09-11 17:05:00
time_end: 2024-09-11 17:30:00
room: California West
track: Airflow & ...
day: 20242
timeslot: 74
gridarea: "16/3/17/4"
images: 
 - /images/sessions/2024/airflow-multi-cluster.jpg
slides: 2024/65-Airflow-and-multi-cluster-Slurm-working-together.pdf
video: https://youtu.be/ol6k7df3Kr0
---

Meteosim provides environmental services, mainly based on weather and air quality intelligence, and helps customers make operational and tactical decisions and understand their companies' environmental impact. We introduced Airflow a couple of years ago to replace a huge Crontab file and we currently have around 7000 DAG Runs per day. 
 
 
 
 In this presentation we will introduce the hardest challenge we had to overcome: adapting Airflow to run on multiple Slurm-managed HPC clusters by using deferrable operators. Slurm is an open-source cluster manager, used especially in science-based companies or organizations and many supercomputers worldwide. By using Slurm our simulations run on bare metal nodes, eliminating overhead and speeding up the intensive calculations.
 
 
 
 Moreover, we will present our use case: how we use Airflow to provide our services and how we streamlined the DAG creation process, so our Product Engineers need to write a few lines of code and all DAGs are standardized and stored in a database.