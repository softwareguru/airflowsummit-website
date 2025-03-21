---
title: "Event-based DAG Parsing: No more F5ing in the UI"
slug: event-based-dag-parsing-no-more-f5ing-in-the-ui
speakers:
 - Bas Harenslak
time_start: 2023-09-19T14:30:00-04:00
time_end: 2023-09-19T14:55:00-04:00
room: Ballroom A-B
track: New features/roadmap
day: 1
timeslot: 10
images:
 - /images/sessions/2023/BasHarenslak.jpg
slides: 2023/ab1-1430-EventBasedDAGs.pdf
video: https://youtu.be/UkV1CAOul2w
---

Have you ever added a DAG file and had no clue what happened to it? You're not alone! With default settings, Airflow can wait up to 5 minutes before processing new DAG files.

In this talk, I'll discuss the implementation of an event-based DAG parser that immediately processes changes in the DAGs folder. As a result, changes are reflected immediately in the Airflow UI. In this talk I will cover: 
 
 * A demonstration of the event-based DAG parser and the fast Airflow UI experience 
 * How the current DAG parser implementation and configuration works
 * How an event-based DAG parser is implemented
