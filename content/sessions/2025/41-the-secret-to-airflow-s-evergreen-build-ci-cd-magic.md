---
title: "The Secret to Airflow's Evergreen Build: CI/CD magic"
slug: the-secret-to-airflow-s-evergreen-build-ci-cd-magic
speakers:
 - Amogh Desai
 - Jarek Potiuk
 - Pavan kumar Gopidesu
topics:
 - Community
time_start: 2025-10-08 10:30:00
time_end: 2025-10-08 11:10:00
room: Columbia A
track: Community
day: 20252
timeslot: 41
gridarea: 4/2/5/3
images:
slides:
video: 
---

Have you ever wondered why Apache Airflow builds are asymptotically(*) green? That thrive for “perennial green build” is not magic, it’s the result of continuous, often unseen engineering effort within our CI/CD pipelines & dev environments. This dedication ensures that maintainers can work efficiently & contributors can onboard smoothly.

To tackle the ever growing contributor base, we have a CI/CD team run by volunteers putting in significant work in the foundational tooling. In this talk, we reveal some innovative solutions we have implemented like:
* Handling GitHub Actions pull_request_target challenges
* Restructuring the repo for better clarity
* Slack bot for CI failure alerts
* A cherry picker workflow for releases
* Pre-commit hooks
* Faster website and image builds
* Tackling the new GitHub API rate limits
* Solving chicken-and-egg build issues during releases

Join us to understand the "why" & "how" behind these infra components. You'll gain insights into the continuous effort required to support a thriving open-source project like Airflow and, hopefully, be inspired to contribute to these areas.
(*) asymptotically = we fix failures as quickly as we can when they happen