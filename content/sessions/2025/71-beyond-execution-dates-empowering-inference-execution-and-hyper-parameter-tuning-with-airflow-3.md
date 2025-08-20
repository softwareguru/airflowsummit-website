---
title: "Beyond Execution Dates: Empowering inference execution and hyper-parameter tuning with Airflow 3"
slug: beyond-execution-dates-empowering-inference-execution-and-hyper-parameter-tuning-with-airflow-3
speakers:
 - Ankit Chaurasia
 - Rahul Vats
topics:
 - Airflow 3
time_start: 2025-10-08 14:00:00
time_end: 2025-10-08 14:25:00
room: Columbia D
track: Airflow 3
day: 20252
timeslot: 71
gridarea: 9/4/10/5
slides:
video:
images:
 - /images/sessions/2025/beyond-execution-dates.png
---

In legacy Airflow 2.x, each DAG run was tied to a unique "execution_date." By removing this requirement, Airflow can now directly support a variety of new use cases, such as model training and generative AI inference, without the need for hacks and workarounds typically used by machine learning and AI engineers. 

In this talk, we will delve into the significant advancements in Airflow 3 that enable GenAI and MLOps use cases, particularly through the changes outlined in AIP 83. We’ll cover key changes like the renaming of "execution_date" to "logical_date," along with the allowance for it to be null, and the introduction of the new "run_after" field which provides a more meaningful mechanism for scheduling and sorting. Furthermore, we’ll discuss how by removing the uniqueness constraint, Airflow 3 enables multiple parallel runs, empowering diverse triggering mechanisms and easing backfill logic with a real-world demo.