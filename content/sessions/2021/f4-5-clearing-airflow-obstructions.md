---
id: f4-5
title: "Clearing Airflow obstructions"
url: /sessions/2021/clearing-airflow-obstructions
speakers:
 - Tatiana Al-Chueyr Martins
time_start: 2021-07-15T17:30:00.000Z
time_end: 2021-07-15T18:20:00.000Z
block: f
slot: 4
format: presentation
aliases:
 - /sessions/Clearing-Airflow-obstructions
crowdcast_id: 40
video: https://youtu.be/5zAv_GTUEZw

---

Apache Airflow aims to speed the development of workflows, but developers are always ready to add bugs here and there.

 This talk illustrates a few pitfalls faced while developing workflows at the BBC to build machine learning models. The objective is to share some lessons learned and, hopefully, save others time.

 Some of the topics covered, with code examples:
 * Tasks unsuitable to be run from within Airflow executors
 * Plugins misusage
 * Inconsistency while using an operator
 * (Mis)configuration
 * What to avoid during a workflow deployment
 * Consequences of non-idempotent tasks
