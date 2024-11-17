---
title: "Overcoming Custom Python Package Hurdles in Airflow"
slug: overcoming-custom-python-package-hurdles-in-airflow
speakers:
 - Amogh Desai
 - Shubham Raj
time_start: 2024-09-10 17:10:00
time_end: 2024-09-10 17:35:00
room: California West
track: Airflow & ...
day: 20241
timeslot: 36
gridarea: "14/3/15/4"
images: 
 - /images/sessions/2024/overcoming-python.jpg
slides: 2024/28-Overcoming-Custom-Python-Package-Hurdles-in-Airflow.pdf
video: https://youtu.be/Vw5D4wm3JaM
---

DAG Authors, while constructing DAGs, generally use native libraries provided by Airflow in conjunction with python libraries available over public PyPI repositories.
 
But sometimes, DAG authors need to construct DAG using libraries that are either in-house or not available over public PyPI repositories. This poses a serious challenge for users who want to run their custom code with Airflow DAGs, particularly when Airflow is deployed in a cloud-native fashion.
 
Traditionally, these packages are baked in Airflow Docker images. This won’t work post deployment and is super impractical if your library is under development.
 
We propose a solution that creates a dedicated Airflow global python environment that dynamically generates the requirements, establishes a version-compatible pyenv adhering to Airflow’s policies, and manages custom pip repository authentication seamlessly. Importantly, the service executes these steps in a fail-safe manner, not compromising core components.
 
Join us as we discuss the solution to this common problem, touching upon the design, and seeing the solution in action. We also candidly discuss some challenges, and the shortcomings of the proposed solution.