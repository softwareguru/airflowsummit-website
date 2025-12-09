---
title: "AWS Lambda Executor: The Speed of Local Execution with the Advantages of Remote"
slug: aws-lambda-executor-the-speed-of-local-execution-with-the-advantages-of-remote
speakers:
 - Niko Oliveira
topics:
 - Airflow intro/overview
time_start: 2025-10-09 15:00:00
time_end: 2025-10-09 15:25:00
room: Beckler
track: Airflow intro/overview
day: 20253
timeslot: 168
gridarea: 12/5/13/6
slides: 2025/aws-lambda-executor-the-speed-of-local-execution.pdf
video: https://youtu.be/iYkTEAre70E
images:
 - /images/sessions/2025/aws-lambda-executor.png
---

Apache Airflow's executor landscape has traditionally presented users with a clear trade-off: choose either the speed of local execution or the scalability, isolation and configurability of remote execution. The AWS Lambda Executor introduces a new paradigm that bridges this gap, offering near-local execution speeds with the benefits of remote containerization.

This talk will begin with a brief overview of Airflow's executors, how they work and what they are responsible for, highlighting the compromises between different executors. We will explore the emerging niche for fast, yet remote execution and demonstrate how the AWS Lambda Executor fills this space.
We will also address practical considerations when using such an executor, such as working within Lambda's 15 minute execution limit, and how to mitigate this using multi-executor configuration.

Whether you're new to Airflow or an experienced user, this session will provide valuable insights into task execution and how you can combine the best of both local and remote execution paradigms.