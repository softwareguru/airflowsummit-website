---
title: "Adaptive Memory Scaling for Robust Airflow Pipelines"
slug: adaptive-memory-scaling-for-robust-airflow-pipelines
speakers:
 - Cyrus Dukart
 - David Sacerdote
 - Jason Bridgemohansingh
time_start: 2024-09-12 12:30:00
time_end: 2024-09-12 13:15:00
room: California East
track: Use cases
day: 20243
timeslot: 94
gridarea: "8/2/10/3"
images: 
 - /images/sessions/2024/adaptive-memory-scaling.jpg
slides: 2024/76-Adaptive-Memory-Scaling-for-Robust-Airflow-Pipelines.pdf
video: https://youtu.be/1AZkGkgdUoQ
---

At Vibrant Planet, we're on a mission to make the world's communities and ecosystems more resilient in the face of climate change. Our cloud-based platform is designed for collaborative scenario planning to tackle wildfires, climate threats, and ecosystem restoration on a massive scale. 
 
In this talk we will dive into how we are using Airflow. Particularly we will focus on how we're making Airflow pipelines smarter and more resilient, especially when dealing with the task of processing large satellite imagery and other geospatial data. 
 
 
 
 1. Self-Healing Pipelines: 
 
 Discuss our self-healing pipelines which identify likely out-of-memory events and incrementally allocate more memory for task instance retries, ensuring robust and uninterrupted workflow execution.
 
 
 
 2. Initial Memory Recommendations: 
 
 We'll discuss how we set intelligent initial memory allocations for each task instance, enhancing resource efficiency from the outset.