---
title: "Scale and Security : How Autodesk Securely Develops and Tests PII Pipelines with Airflow"
slug: scale-and-security-how-autodesk-securely-develops-and-tests-pii-pipelines-with-airflow
speakers:
 - Bhavesh Jaisinghani
time_start: 2024-09-12 10:30:00
time_end: 2024-09-12 10:55:00
room: Elizabethan A+B
track: Use cases
day: 20243
timeslot: 84
gridarea: "4/4/5/5"
images: 
 - 
---

In today's data-driven era, ensuring data reliability and enhancing our testing and development capabilities are paramount. Local unit testing has its merits but falls short when dealing with the volume of big data. One major challenge is running Spark jobs pre-deployment to ensure they produce expected results and handle production-level data volumes.

In this talk, we will discuss how Autodesk leveraged Astronomer to improve pipeline development. We'll explore how it addresses challenges with sensitive and large data sets that cannot be transferred to local machines or non-production environments. Additionally, we'll cover how this approach supports over 10 engineers working simultaneously on different feature branches within the same repo.

We will highlight the benefits, such as conflict-free development and testing, and eliminating concerns about data corruption when running DAGs on production Airflow servers.

Join me to discover how solutions like Astronomer empower developers to work with increased efficiency and reliability. This talk is perfect for those interested in big data, cloud solutions, and innovative development practices.