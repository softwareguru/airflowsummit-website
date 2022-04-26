---
id: i5
title: "Skip tasks to make your debugging easy"
url: /sessions/2022/skip-tasks-to-make-your-debugging-easy
speakers:
 - Howie Wang
time_start: 2022-05-26T05:40:00.000Z
time_end: 2022-05-26T05:50:00.000Z
format: "Presentation"
hosted_by: "Melbourne"
presence: "remote"
block: i
slot: 5
---

In Apple, we are building a self-serve data platform based on Airflow. Self-serve means users can create, deploy and run their DAGs freely. With provided logs and metrics, users are able to test or troubleshot DAGs on their own. Today, a common use case is, users want to test one or a few tasks in their DAG. However, when they trigger the DAG, all tasks instead of just the ones people are interested will run. To save time and resources, lots of users choose to manually mark complete for each tasks to skip. Can we do better than that? Is there an easy-peasy way to skip tasks?
 
 In this lightning talk, we would like to share the challenges we had, the solution we came up with, and the lesson we learned.