---
title: "Introducing airflowctl: A CLI to streamline getting started with Airflow"
slug: introducing-airflowctl
speakers:
 - Kaxil Naik
time_start: 2023-09-19T12:00:00-04:00
time_end: 2023-09-19T12:25:00-04:00
day: 1
timeslot: 6
room: York
track: Airflow basics
images:
 - /images/sessions/2023/KaxilNaik.jpg

---

New users starting with Airflow frequently encounter several challenges, ranging from the complexities of Containers and virtual environments to the Python dependency hell. Moreover, their familiarity with tools such as Docker, docker-compose, and Helm might be somewhat limited and even overkill. In contrast, seasoned Airflow users encounter their problems, encompassing configuration conflics with ongoing Airflow projects and intricacies stemming from Docker and docker-compose configurations and lack of visibility into all the projects.

With airflowctl, users can install & setup Airflow using a single command. For existing users, they can use it to manage multiple Airflow projects with different Airflow versions on the same machine. This allows creating & debugging DAGs in an IDE seamlessly.

Agenda for the call:
- Why airflowctl?
- Goal
- Current functionality & Demo
- Vision / Roadmap