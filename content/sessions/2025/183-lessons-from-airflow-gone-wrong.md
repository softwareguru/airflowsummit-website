---
title: "Lessons from Airflow gone wrong: How to set yourself up to scale successfully"
slug: lessons-from-airflow-gone-wrong
speakers:
 - Annie Friedman
 - Caitlin Petro
time_start: 2025-10-09 16:15:00
time_end: 2025-10-09 16:40:00
room: Beckler
track: Best practices
day: 20253
timeslot: 183
gridarea: 16/5/17/6
slides:
video:
---

Ever seen a DAG go rogue and deploy itself? Or try to time travel back to 1999? Join us for a light-hearted yet painfully relatable look at how not to scale your Airflow deployment to avoid chaos and debugging nightmares.

We'll cover the classics: hardcoded secrets, unbounded retries (hello, immortal task!), and the infamous spaghetti DAG where 200 tasks are lovingly connected by hand and no one dares open the Airflow UI anymore. If you've ever used datetime.now() in your DAG definition and watched your backfills implode, this talk is for you.

From the BashOperator that became sentient to the XCom that tried to pass a whole Pandas DataFrame and the key to your mother's house, we'll walk through real-world bloopers with practical takeaways. You'll learn why overusing PythonOperator is a recipe for mess, how not to use sensors unless you enjoy resource starvation, and why scheduling in local timezones is basically asking for a daylight savings time horror story.
Other highlights include:

Over-provisioning resources in KubernetesPodOperator: many teams allocate excessive memory/CPU "just in case", leading to cluster contention and resource waste.

Dynamic task mapping gone wild: 10,000 mapped tasks later… the scheduler is still crying.

SLAs used as data quality guarantees: creating alerts so noisy, nobody listens.
Design-free DAGs: no docs, no comments, no idea why a task has a 3-day timeout.
Finally, we'll round it out with some dos and don'ts: using environment variables, avoiding memory-hungry monolith DAGs, skipping global imports, and not allocating 10x more memory "just in case."
Whether you're new to Airflow or battle-hardened from a thousand failed backfills, come learn how to scale your pipelines without losing your mind (or your cluster).