---
title: "Simplified user management in Airflow"
slug: simplified-user-management-in-airflow
speakers:
 - Vincent Beck
time_start: 2024-09-11 17:05:00
time_end: 2024-09-11 17:30:00
room: Elizabethan A+B
track: New features
day: 20242
timeslot: 75
gridarea: "16/4/17/5"
images: 
 - /images/sessions/2024/simplified-user-management.jpg
slides: 2024/68-Simplified-user-management-in-Airflow.pdf
video: 
---

Before Airflow 2.9, user management was part of core Airflow, therefore modifying it or customizing it to fit user needs was not an easy process. Authentication and authorization managers (auth managers), is a new concept introduced in Airflow 2.9. It was introduced as extensible user management (AIP-56), allowing Airflow users to have a flexible way to integrate with organization's identity services. Organizations want a single place to manage permissions and FAB (Flask App Builder) made it difficult to achieve. In this talk, after explaining the concept of auth managers and why we built this, we will show you how you can leverage the new auth manager interface to build an authorization service for Airflow based on your existing identity provider. We will see that auth managers can be leveraged to change considerably how users and their permissions are managed in an Airflow environment. 
 
 
 
 Finally, we will dive deep into the AWS auth manager as an alternative auth manager and see some different usages as examples.