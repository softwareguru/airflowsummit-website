---
title: "Deadlines for DAGs: What's Shipped and What's Next"
slug: deadlines-for-dags-what-s-shipped-and-what-s-next
speakers:
 - Sean Ghaeli
topics:
 - Builder
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Airflow's legacy SLA (Service level agreement) feature let users set a maximum expected duration for a DAG run and receive an email when it was exceeded, but it was inflexible and hard to configure. Deadline Alerts replaced it in 3.1 with a general-purpose system for time-based alerting. Since then, two release cycles have reshaped the feature.

Callbacks now run in supervised subprocesses with access to Connections, Variables, and Assets, which means they can query your infrastructure and respond to problems, not just send a notification. Deadline status is visible in the UI Grid view and DAG run overview. Named deadlines let you attach multiple alerts to a single DAG for different stakeholders. OpenLineage captures deadline events. And fixes for duplicate callbacks under HA schedulers and migration performance have made the feature production-solid.

As one of the developers of Deadline Alerts, I'll walk through these changes and show callback patterns that take advantage of the new execution model. I'll close with where the feature is going: deadlines that attach to individual tasks and assets. The end goal is for Deadline Alerts to make time constraints something the scheduler understands and acts on, not just something you get alerted about after the fact.