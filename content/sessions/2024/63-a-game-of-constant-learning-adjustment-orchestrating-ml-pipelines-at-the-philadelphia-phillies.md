---
title: "A Game of Constant Learning & Adjustment: Orchestrating ML Pipelines at the Philadelphia Phillies"
slug: a-game-of-constant-learning-adjustment-orchestrating-ml-pipelines-at-the-philadelphia-phillies
speakers:
 - Mike Hirsch
 - Sophie Keith
time_start: 2024-09-11 15:05:00
time_end: 2024-09-11 15:30:00
room: California East
track: Use cases
day: 20242
timeslot: 63
gridarea: "12/2/13/3"
images: 
 - /images/sessions/2024/game-constant-learning.jpg
video: https://youtu.be/TH0SSdAZGPg
---

When developing Machine Learning (ML) models, the biggest challenges are often infrastructural. How do we deploy our model and expose an inference API? How can we retrain? Can we continuously evaluate performance and monitor model drift? 
 
 
 
 In this talk, we will present how we are tackling these problems at the Philadelphia Phillies by developing a suite of tools that enable our software engineering and analytics teams to train, test, evaluate, and deploy ML models - that can be entirely orchestrated in Airflow. This framework abstracts away the infrastructural complexities that productionizing ML Pipelines presents and allows our analysts to focus on developing robust baseball research for baseball operations stakeholders across player evaluation, acquisition, and development.
 
 
 
 We’ll also look at how we use Airflow, MLflow, MLServer, cloud services, and GitHub Actions to architect a platform that supports our framework for all points of the ML Lifecycle.