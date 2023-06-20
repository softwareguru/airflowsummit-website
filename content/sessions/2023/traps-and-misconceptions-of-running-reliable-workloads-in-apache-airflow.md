---
title: "Traps and misconceptions of running reliable workloads in Apache Airflow"
slug: traps-and-misconceptions-of-running-reliable-workloads-in-apache-airflow
speakers:
 - Bartosz Jankiewicz
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Use cases
session_type: breakout
---

Reliability is a complex and important topic. I will focus on both reliability definition and best practices.



I will begin by reviewing the Apache Airflow components that impact reliability. I will subsequently examine those aspects, showing the single points of failure, mitigations, and tradeoffs.



The journey starts with the scheduling process. I will focus on the aspects of Scheduler infrastructure and configuration that address reliability improvements. It doesn't run in a vacuum therefore I'll share my observations on the reliability aspect of Scheduler infrastructure.



We recommend tasks to be idempotent but that is not always possible. I will share the challenges of running user's code in the distributed architecture of Cloud Composer. I will refer to the volatility of some cloud resources and mitigation methods in various scenarios. Deferrability plays important part in the reliability, but there are also other elements we shouldn't ignore.