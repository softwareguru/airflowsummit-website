---
title: "Anatomy of a Task Instance: From Scheduled to Done"
slug: anatomy-of-a-task-instance-from-scheduled-to-done
speakers:
 - Cedrik Neumann
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

In this session I will provide a deep dive into a task instance's lifetime. From when the scheduler decides for it to be scheduled until it is marked as success or failed.

We will explore when in the process concepts like concurrency, pools and priority weights apply, what it means for a task to be "queued" and where things like cluster policies, operator links, callbacks and event listeners are evaluated.

The goal is to have a non-technical reference of the inner workings of Airflow applicable to the day-to-day of Dag and Plugin authors.