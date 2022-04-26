---
id: i1
title: "Introducing Astro Flow: The next generation of DAG authoring"
url: /sessions/2022/introducing-astro-flow:-the-next-generationdag-authoring
speakers:
 - Daniel Imberman
time_start: 2022-05-26T03:00:00.000Z
time_end: 2022-05-26T03:40:00.000Z
format: "Presentation"
hosted_by: "Melbourne"
presence: "remote"
block: i
slot: 1
---

Imagine if you could chain together SQL models using nothing but python, write functions that treat Snowflake tables like dataframes and dataframes like SQL tables. Imagine if you could write a SQL airflow DAG using only python or without using any python at all. 
 
 
 
 With Astro SDK, we at Astronomer have gone back to the drawing board around fundamental questions of what DAG writing could look like. Our goal is to empower Data Engineers, Data Scientists, and even the Business Analysts to write Airflow DAGs with code that reflects the data movement, instead of the system configuration. Astro will allow each group to focus on producing value in their respective fields with minimal knowledge of Airflow and high amounts of flexibility between SQL or python-based systems.
 
 
 
 This is way beyond just a new way of writing DAGs. This is a universal agnostic data transfer system. Users can run the exact same code against different databases (snowflake, bigquery, etc.) and datastores (GCS, S3, etc.) with no changes except to the connection IDs. Users will be able to promote a SQL flow from their dev postgres to their prod snowflake with a single variable change.
 
 
 
 We are ecstatic to reveal over eight months of work around building a new open-source project that will significantly improve your DAG authoring experience!