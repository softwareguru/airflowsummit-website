---
title: "Event-driven Data Pipelines with Apache Airflow"
slug: event-driven-data-pipelines-with-apache-airflow
speakers:
 - John Jackson

time_start: 2024-09-10 11:00:00
time_end: 2024-09-10 11:45:00
room: Georgian
track: Best practices
day: 20241
timeslot: 8
gridarea: "5/5/6/6"
images: 
 - /images/sessions/2024/event-driven.jpg
slides: 
video: https://youtu.be/bk9NStntfi0
---

Airflow is all about schedules…we use CRON strings and Timetable to define schedules, and there’s an Airflow Scheduler component that manages those timetables, and a lot more, to ensure that DAGs and tasks are addressed based on those schedules.
 
 
 
 But what do you do if your data isn’t available on a schedule? What if data is coming from many sources, at varying times, and your job is to make sure it’s all as up-to-date as possible? An event-driven data pipeline may be the answer.
 
 
 
 An event-driven architecture (or EDA) is an architecture pattern that uses events to decouple an application’s components. It relies on external events, not an internal schedule, to create loosely coupled data pipelines that determine when to take action, and what actions to take. In this session, we will discuss the design considerations when using Airflow in an EDA and the tools Airflow has to make this happen, including Datasets, REST API, Dynamic Task Mapping, custom Timetables, Sensors, and queues.