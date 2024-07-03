---
title: "Using Operational Data"
url: /sessions/using-operational-data
speakers:
 - Olivier Daneau
track:
 - Best practices
time_start: 2021-07-18T16:00:00.000Z
time_end: 2021-07-18T16:45:00.000Z
draft: false
---

Cost management is a continuous challenge for our data teams at Astronomer. Understanding the expenses associated with running our workflows is not always straightforward, and identifying which process ran a query causing unexpected usage on a given day can be time-consuming.

In this talk, we will showcase an Airflow Plugin and specific DAGs developed and used internally at Astronomer to track and optimize the costs of running DAGs. Our internal tool monitors Snowflake query costs, provides insights, and sends alerts for abnormal usage. With it, Astronomer identified and refactored its most costly DAGs, resulting in an almost 25% reduction in Snowflake spending.

We will demonstrate how to track Snowflake-related DAG costs and discuss how the tool can be adapted to any database supporting query tagging like BigQuery, Oracle, and more.

This talk will cover the implementation details and show how Airflow users can effectively adopt this tool to monitor and manage their DAG costs.