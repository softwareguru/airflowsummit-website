---
title: "Airflow at UniCredit: Our journey from mainframe scheduling to modern data processing"
slug: airflow-at-unicredit-our-journey-from-mainframe-scheduling-to-modern-data-processing
aliases:
 - /sessions/2023/the-airflow-experience-at-unicredit
speakers:
 - Jan Pawlowski
 - Jędrzej Matuszak
time_start: 2023-09-20T15:00:00-04:00
time_end: 2023-09-20T15:25:00-04:00
room: Ballroom C-D
track: Use cases
day: 2
timeslot: 11
---

Representing the Murex Reporting team at UniCredit we would like to present our journey with Airflow, and how over the past two years it enabled us to automate and simplify our batch workflows. Comparing to our previous rigid mainframe scheduling approach, we have created a robust and scalable framework complete with a CI/CD process, bringing our time to market of scheduling changes down from 3 days to 1. Basing our solution on DAG networks joined by ResumeDagRunOperators and an array of custom-built plugins (such as static time predecessors) we were able to replicate the scheduling of our overnight ETL processes (consisting of approx. 8000 tasks with many-to-many dependencies) in Airflow, satisfying our bank reporting SLAs without performance regression and gaining massively improved process visibility and control. Our presentation will illustrate our journey and explore some of these customizations, which venture outside of Airflow's core functionalities.

