---
id: 
title: "Love for writing deferrable operators. Why and how to defer?"
url: /sessions/2022/love-for-writing-deferrable-operators
speakers:
 - Ankit Chaurasia
block: 
slot: 
track: Community
time_start: 2022-01-01T17:00:00.000Z
time_end: 2022-01-01T18:00:00.000Z

---

Have you faced a scenario where 100 worker slots are available to run the Tasks, but you have 100 DAGs waiting on a Sensor that’s currently running but idle, waiting for something to happen? Ultimately, you got frustrated as you could not run anything else - even though your entire Airflow cluster was essentially idle. This is exactly where the concept of Deferrable Operators is very useful. 

This talk aims to give a brief introduction to solving this problem using Deferrable or Async Operators and how to implement it for your use case.
 
This talk also aims to explain: 
 - Introduction to deferrable operator
 - Introduction to Triggers
 - Using deferrable operator - real-world use case
 - Writing deferrable operators
 - Triggering deferral
 - Writing Triggers
 - Example of deferrable S3 Operator
 - Advantages over Smart Sensors and reschedule mode for sensor
 - Guide to implement your deferrable operator with astronomer-providers repository as an example to start with
 - References for useful concepts and libraries: Concurrency, Python asyncio