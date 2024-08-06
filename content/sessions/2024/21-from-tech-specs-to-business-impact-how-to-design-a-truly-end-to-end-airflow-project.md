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

There are many Airflow tutorials. However, many don’t show the full process of sourcing, transforming, testing, alerting, documenting, and finally supplying data. This talk with go over how to piece together an end-to-end Airflow project that transforms raw data to be consumable by the business. It will include how various technologies can all be orchestrated by Airflow to satisfy the needs of analysts, engineers, and business stakeholders. Each step and technology mentioned will be something that we at AngelList use, and code snippets will be sprinkled throughout so that attendees can implement this project within their organizations. 
 
 
 
 The talk will be divided into the following sections:
 
 
 
 1. Introduction: Introducing the business problem and how we came up with the solution design
 
 2. Data sourcing: Fetching and storing API data using basic operators and hooks
 
 3. Transformation and Testing: How to use dbt to build and test models based on the raw data
 
 4. Alerting: Alerting the necessary parties when any part of this DAG fails using Elementary and Slack
 
 5. Documentation and Consumption: How to sync data documentation to Metabase and dbt docs for easy consumption and lineage