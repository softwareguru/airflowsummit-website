---
title: "Using Airflow operational data to optimize Cloud services"
slug: using-airflow-operational-data-to-optimize-cloud-services
speakers:
 - Olivier Daneau
time_start: 2024-09-12 14:35:00
time_end: 2024-09-12 15:00:00
room: California East
track: Best practices
day: 20243
timeslot: 101
gridarea: "12/2/13/3"
images: 
 - /images/sessions/2024/using-operational-data.jpg
---

Cost management is a continuous challenge for our data teams at Astronomer. Understanding the expenses associated with running our workflows is not always straightforward, and identifying which process ran a query causing unexpected usage on a given day can be time-consuming.
 
In this talk, we will showcase an Airflow Plugin and specific DAGs developed and used internally at Astronomer to track and optimize the costs of running DAGs. Our internal tool monitors Snowflake query costs, provides insights, and sends alerts for abnormal usage. With it, Astronomer identified and refactored its most costly DAGs, resulting in an almost 25% reduction in Snowflake spending. 
 
We will demonstrate how to track Snowflake-related DAG costs and discuss how the tool can be adapted to any database supporting query tagging like BigQuery, Oracle, and more. 
 
This talk will cover the implementation details and show how Airflow users can effectively adopt this tool to monitor and manage their DAG costs.