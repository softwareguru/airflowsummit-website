---
title: "Beyond the bundle - evolving DAG parsing in Airflow 3"
slug: beyond-the-bundle-evolving-dag-parsing-in-airflow-3
speakers:
 - Igor Kholopov
topics:
 - Roadmap
time_start: 2025-10-08 14:30:00
time_end: 2025-10-08 14:55:00
room: Columbia C
track: Roadmap
day: 20252
timeslot: 77
gridarea: 10/3/11/4
slides:
video:
images:
 - /images/sessions/2025/beyond-the-bundle.png
---

Airflow 3 made some great strides with AIP-66, introducing the concept of a DAG bundle.
This successfully challenged one of the fundamental architectural limitations of original Airflow design of how DAGs are deployed, bringing the structure to something that often had to be operated as a pile of files in the past.
However, we believe that this by no means should be the end of the road when it comes to making the DAG management easier, authoring more accessible to a broader audience, and integration with Data Agents smoother.
We believe that the next step in Airflow’s evolution is in having a native option to break away from the necessity of having a real file in file systems on multiple components to have your DAG up and running. This is what we are hoping to achieve as part of AIP-85 - extendable DAG parsing control.
In this talk I’d like to give a detailed overview of how we want to make it happen and show the examples of the valuable integrations we hope to unblock with it.
