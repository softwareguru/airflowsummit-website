---
title: "From Tech Specs to Business Impact: How to Design A Truly End-to-End Airflow Project"
slug: from-tech-specs-to-business-impact-how-to-design-a-truly-end-to-end-airflow-project
speakers:
 - Taylor Facen
time_start: 2024-09-10 14:35:00
time_end: 2024-09-10 15:00:00
room: Georgian
track: Best practices
day: 20241
timeslot: 21
gridarea: "9/5/10/6"
images: 
 - /images/sessions/2024/from-tech-specs.jpg
---

There are many Airflow tutorials. However, many don’t show the full process of sourcing, transforming, testing, alerting, documenting, and finally supplying data. This talk with go over how to piece together an end-to-end Airflow project that transforms raw data to be consumable by the business. It will include how various technologies can all be orchestrated by Airflow to satisfy the needs of analysts, engineers, and business stakeholders. 

The talk will be divided into the following sections:

    Introduction: Introducing the business problem and how we came up with the solution design
    Data sourcing: Fetching and storing API data using basic operators and hooks
    Transformation and Testing: How to use dbt to build and test models based on the raw data
    Alerting: Alerting the necessary parties when any part of this DAG fails using Slack
    Consumption: How to make dynamic data accessible to business stakeholders