---
title: "Flexible DAG Trigger Forms (AIP-50)"
slug: flexible-dag-trigger-forms-aip-50
speakers:
 - Jens Scheffler
 - Christian Schilling
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
---

As user of Airflow we often use DagRun.conf attributes to control content and flow of a DAG run. Previously the Airflow UI only allowed to launch via JSON in the UI. This was technically feasible but not user friendly. A user needs to model, check and understand the JSON and enter parameters manually without the option to validate before trigger.



Similar like Jenkins or Github/Azure pipelines we desire an UI option to trigger with a UI and specifying parameters.



With Airflow 2.6.0 now the DAG.params are used to render a nice entry form and with a bit of options a user friendly trigger UI can be implemented.



This session is showing how the new feature works and provides some examples how to use it for your purposes.