---
id: h1
title: "Building a Scalable & Isolated Architecture for Preprocessing Medical Records"
url: /sessions/2021/building-scalable-isolated-architecture-for-preprocessing-medical-records
speakers:
 - Mikaela Pisani
 - Anthony Figueroa
time_start: 2021-07-16T16:00:00.000Z
time_end: 2021-07-16T16:25:00.000Z
block: h
slot: 1
format: presentation
aliases:
 - /sessions/Building-a-Scalable-&-Isolated-Architecture-for-Preprocessing-Medical-Records
crowdcast_id: 48
video: https://youtu.be/1d9-X0UxqAM
slides: 2021/h1-Rootstrap.pdf
---

After performing several experiments with Airflow, we reached the best architectural design for processing text medical records in scale. Our hybrid solution uses Kubernetes, Apache Airflow, Apache Livy, and Apache cTAKES. Using Kubernetes’ containers has the benefit of having a consistent, portable, and isolated environment for each component of the pipeline.
 With Apache Livy, you can run tasks in a Spark Cluster at scale. Additionally, Apache cTAKES helps with the extraction of information from electronic medical records clinical free-text by using natural language processing techniques to identify codable entities, temporal events, properties, and relations.
