---
title: "DAGLint: Elevating Airflow DAG Quality Through Automated Linting"
slug: daglint-elevating-airflow-dag-quality-through-automated-linting
speakers:
 - Snir Israeli
topics:
 - Use cases
time_start: 2025-10-07 14:30:00
time_end: 2025-10-07 14:55:00
room: Beckler
track: Use cases
day: 20251
timeslot: 20
gridarea: 8/5/9/6
slides:
video:
images:
 - /images/sessions/2025/daglint-elevating-airflow.png
---

Maintaining consistency, code quality, and best practices for writing Airflow DAGs between teams and individual developers can be a significant challenge. Trying to achieve it using manual code reviews is both time-consuming and error-prone.

To solve this at Next, we decided to build a custom, internally developed linting tool for Airflow DAGs, to help us evaluate their quality and uniformity - we call it - DAGLint.

In this talk I am going to share why we chose to implement it, how we built it, and how we use it to elevate our code quality and standards throughout the entire Data engineering group.

This tool supports our day-to-day development process, provides us with a visual analysis of the state of our entire code base, and allows our code reviews to focus on other code quality aspects. We can now easily identify deviations from our defined standards, promote consistency throughout our DAGs repository, and extend the tool with additional new standards introduced to our group.

The talk will cover how you can implement similar solution in your own organization, we also published a blog post on it
https://medium.com/apache-airflow/mastering-airflow-dag-standardization-with-pythons-ast-a-deep-dive-into-linting-at-scale-1396771a9b90