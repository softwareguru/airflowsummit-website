---
title: "Run Airflow tasks on your coffee machine"
slug: run-airflow-tasks-on-your-coffee-machine
speakers:
 - Cedrik Neumann
topics:
 - Airflow 3
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Airflow 3 comes with two new features: Edge execution and the task SDK. Powered by a HTTP API, these make it possible to write and execute Airflow tasks in any language from anywhere.

In this session I will explain some of the APIs needed and show how to interact with them based on an embedded toy worker written in Rust and running on an ESP32-C3. Furthermore I will provide practical tips on writing your own edge worker and how to develop against a running instance of Airflow.