---
title: "Empowering Airflow Users: A Framework for Performance Testing and Transparent Resource Optimization"
speakers:
 - Bartosz Jankiewicz
track:
 - New features
images:
 - /images/sessions/2024/empowering-airflow.jpg 
time_start: 2024-09-10T16:00:00.000Z
time_end: 2024-09-10T16:45:00.000Z
draft: false
---

Apache Airflow is the backbone of countless data pipelines, but optimizing performance and resource utilization can be a challenge. This talk introduces a novel performance testing framework designed to measure, monitor, and improve the efficiency of Airflow deployments. I'll delve into the framework's modular architecture, showcasing how it can be tailored to various Airflow setups (Docker, Kubernetes, cloud providers). By measuring key metrics across schedulers, workers, triggers, and databases, this framework provides actionable insights to identify bottlenecks and compare performance across different versions or configurations.

Attendees will learn:

 * The motivation behind developing a standardized performance testing approach.
 * Key design considerations and challenges in measuring performance across diverse Airflow environments.
 * How to leverage the framework to construct test suites for different use cases (e.g., version comparison).
 * Practical tips for interpreting performance test results and making informed decisions about resource allocation.
 * How this framework contributes to greater transparency in Airflow release notes, empowering users with performance data.