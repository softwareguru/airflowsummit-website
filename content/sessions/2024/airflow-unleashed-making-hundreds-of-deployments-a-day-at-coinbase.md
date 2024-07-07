---
title: "Airflow Unleashed: Making Hundreds of Deployments A Day at Coinbase"
slug: airflow-unleashed-making-hundreds-of-deployments-a-day-at-coinbase
speakers:
 - Jianlong Zhong
track:
 - Airflow & ...
images:
 - /images/sessions/2024/airflow-unleashed.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

At Coinbase, Airflow is the backbone of ELT, supported by a vibrant community of over 500 developers. This vast engagement results in a continuous stream of enhancements, with hundreds of commits tested and released daily. However, this scale of development presents its own set of challenges, especially in deployment velocity.

Traditional deployment methodologies proved inadequate, significantly impeding the productivity of our developers. Recognizing the critical need for a solution that matches our pace of innovation, we developed AirAgent: a bespoke, fully autonomous deployer designed specifically for Airflow. Capable of deploying updates hundreds of times a day on both staging and production environments, AirAgent has transformed our development lifecycle, enabling immediate iteration and drastically improving developer velocity.

This talk aims to unveil the inner workings of AirAgent, highlighting its design principles, deployment strategies, and the challenges we overcame in its implementation. By sharing our journey, we hope to offer insights and strategies that can benefit others in the Airflow community, encouraging a shift towards a high-frequency deployment workflow.