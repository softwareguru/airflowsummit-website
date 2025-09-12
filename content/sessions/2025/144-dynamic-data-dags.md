---
title: "Dynamic DAGs and Data Quality using DAGFactory"
slug: dynamic-dags-data-quality
speakers:
 - Ashir Alam
topics:
 - Use cases
images:

time_start: 2025-10-09 12:30:00
time_end: 2025-10-09 12:55:00
room: Columbia C
track: Use cases
day: 20253
timeslot: 144
gridarea: 8/3/9/4
slides:
video:

---

We have a similar pattern of DAGs running for different data quality dimensions like accuracy, timeliness, & completeness. To do this again and again, we would be duplicating and potentially introducing human error while doing copy paste of code or making people write same code again.

To solve for this, we are doing few things:
 - Run DAGs via DagFactory to dynamically generate DAGs using just some YAML code for all the steps we want to run in our DQ checks.
 - Hide this behind a UI which is hooked to github PR open step, now the user just provides some inputs or selects from dropdown in UI and a YAML DAG is generated for them.

This highlights the potential for DAGFactory to hide Airflow Python code from users and make it more accessible to Data Analysts and Business Intelligence along with normal Software Engg, along with reducing human error. YAML is the perfect format to be able to generate code, create a PR and DagFactory is the perfect fir for that. All of this is running in GCP Cloud Composer.

