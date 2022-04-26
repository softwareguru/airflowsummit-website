---
id: l2
title: "Implementing Event-Based DAGs with Airflow"
url: /sessions/2022/implementing-event-based-dags-with-airflow
speakers:
 - Kenten Danas
time_start: 2022-05-27T01:00:00.000Z
time_end: 2022-05-27T01:20:00.000Z
format: "Technical deep dive / tutorial"
hosted_by: "Seattle"
presence: "onsite"
block: l
slot: 2
---

Needing to trigger DAGs based on external criteria is a common use case for data engineers, data scientists, and data analysts. Most Airflow users are probably aware of the concept of sensors and how they can be used to run your DAGs off of a standard schedule, but sensors are only one of multiple methods available to implement event-based DAGs. In this session, we'll discuss different ways of implementing event-based DAGs using Airflow 2 features like the API and deferrable operators, with a focus on how to determine which method is the most efficient, scalable, and cost-friendly for your use case.