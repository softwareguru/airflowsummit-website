---
title: "Plugin-Maxxing: How we Built a Data Product inside Airflow 3"
url: onlinereconnect/plugin-maxxing
speakers:
 - Bhavani Ravi
track: Data & AI Applications
room: Online
#day: 2026o1
time_start: 2026-11-04 15:00:00
time_end: 2026-11-04 15:30:00
timeslot: 
gridarea: 
images: 

slides:
video: 
---

Changing Airflow scripts because something changed upstream is annoying. 3-hour review cycle for a 4-field change that affects 5 different teams. As a freelancer, I came across this problem multiple times a week.

To solve it, I gave a UI where the end users can map the source and destination and modify the data type and schema however they want. I didn't want to build a whole new scheduler and task management from scratch. Thanks to the Airflow plugin system, we could extend.

React_apps: For your custom/customer facing UI
Fastapi_apps: For your custom backend APIs
DagFactory + Provider: To spin up Dags on the fly
Connections: Airflow's built-in types, no custom credentials store
Metadata: Alongside Airflow Db

By the end of this talk, you will understand how to extend the Airflow plugin system to build your own data product