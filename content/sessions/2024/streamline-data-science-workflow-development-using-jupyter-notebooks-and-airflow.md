---
title: "Streamline data science workflow development using Jupyter notebooks and Airflow"
slug: streamline-data-science-workflow-development-using-jupyter-notebooks-and-airflow
speakers:
 - Neha Singla
 - Sathish kumar Thangaraj
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Jupyter Notebooks are widely used by data scientists and engineers to prototype and experiment with data. However these engineers are often required to work with other data or platform engineers to productionize these experiments due to the complexity in navigating infrastructure and systems. In this talk, we will deep dive into this PR https://github.com/apache/airflow/pull/34840 and share how airflow can be leveraged as a platform to execute notebook pipelines (python, scala or spark) in dynamic environments like Kubernetes for various heterogeneous use cases. We will demonstrate how data scientists can use a Jupyter extension to easily build and manage such pipelines which are executed using Airflow streamlining data science workflow development and supercharging productivity