---
title: "Behaviour Driven Development in Airflow"
slug: behaviour-driven-development-in-airflow
speakers:
 - Ole Christian Langfjaeran
track: Best practices

time_start: 2024-09-11 11:00:00
time_end: 2024-09-11 11:25:00
room: Elizabethan A+B
day: 20242
timeslot: 47
gridarea: "5/4/6/5"

images: 
 - /images/sessions/2024/behaviour-driven.jpg
slides: 2024/44-Behaviour-Driven-Development-in-Airflow.pdf
video: 
---

Behaviour Driven Development can, in the simplest of terms, be described as Test Driven Development, only readable. It is of course more than that, but that is not the aim of this talk. This talk aims to show:
 
 
 
 * How to write tests before you write a single line of Airflow code
 
 * Create reusable and readable steps for setting up tests, in a given-when-then manner.
 
 * Test rendering and execution of your DAG's tasks
 
 * Real world examples from a monorepo containing multiple Airflow projects
 
 
 
 Written only with pytest, and some code I stole from smart people in github.com/apache/airflow/tests