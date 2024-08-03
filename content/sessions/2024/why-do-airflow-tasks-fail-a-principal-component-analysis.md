---
title: "Why Do Airflow Tasks Fail? A Principal Component Analysis"
slug: why-do-airflow-tasks-fail-a-principal-component-analysis
speakers:
 - Julian LaNeve
 - David Xue
track:
 - Use cases
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
images:
 - /images/sessions/2024/why-fail.jpg 
---

There are 3 certainties in life: death, taxes, and data pipelines failing. Pipelines may fail for a number of reasons: you may run out of memory, your credentials may expire, an upstream data source may not be reliable, etc. But there are patterns we can learn from!

Join us as we walk through an analysis we’ve done on a massive dataset of Airflow failure logs. We’ll show how we used principal component analysis and other dimensionality reduction methods to explore the latent space of Airflow task failures in order to cluster, visualize, and understand failures.

We’ll conclude the talk by walking through mitigation methods for common task failure reasons, and walk through how we can use Airflow to build an MLOps platform to turn this one-time analysis into a reliable, recurring activity.