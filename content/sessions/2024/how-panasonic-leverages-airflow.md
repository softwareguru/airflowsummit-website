---
title: "How Panasonic Leverages Airflow"
slug: how-panasonic-leverages-airflow
speakers:
 - Michael Atondo
track:
 - Airflow & ...
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Using various operators to perform daily routines.
Integration with Technologies:
Redis: Acts as a caching mechanism to optimize data retrieval and processing speed, enhancing overall pipeline performance.
MySQL: Utilized for storing metadata and managing task state information within Airflow's backend database.
Tableau: Integrates with Airflow to generate interactive visualizations and dashboards, providing valuable insights into the processed data.
Amazon Redshift: Panasonic leverages Redshift for scalable data warehousing, seamlessly integrating it with Airflow for data loading and analytics.
Foundry: Integrated with Airflow to access and process data stored within Foundry's data platform, ensuring data consistency and reliability.
Plotly Dashboards: Employed for creating custom, interactive web-based dashboards to visualize and analyze data processed through Airflow pipelines.
GitLab CI/CD Pipelines: Utilized for version control and continuous integration/continuous deployment (CI/CD) of Airflow DAGs (Directed Acyclic Graphs), ensuring efficient development and deployment of workflows.