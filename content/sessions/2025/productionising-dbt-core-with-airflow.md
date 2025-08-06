---
title: "Productionising dbt-core with Airflow"
slug: productionising-dbt-core-with-airflow
speakers:
 - Tatiana Al-Chueyr Martins
 - Pankaj Singh
 - Pankaj Koti
topics:
 - Airflow & ...
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
draft: true
---

As a popular open-source library for analytics engineering, dbt is often combined with Airflow. Orchestrating and executing dbt models as DAGs ensures an additional layer of control over tasks, observability, and provides a reliable, scalable environment to run dbt models. 

This workshop will cover a step-by-step guide to Cosmos (https://github.com/astronomer/astronomer-cosmos), a popular open-source package from Astronomer that helps you quickly run your dbt Core projects as Airflow DAGs and Task Groups, all with just a few lines of code. We’ll walk through:

* Running and visualising your dbt transformations
* Managing dependency conflicts
* Defining database credentials (profiles)
* Configuring source and test nodes
* Using dbt selectors
* Customising arguments per model
* Addressing performance challenges
* Leveraging deferrable operators
* Visualising dbt docs in the Airflow UI
* Example of how to deploy to production
* Troubleshooting

We encourage participants to bring their dbt project to follow this step-by-step workshop.
