---
title: "Advanced Deadine Alerts: Writing your own custom References and Callbacks"
slug: advanced-deadine-alerts-writing-your-own-custom-references-and-callbacks
speakers:
 - Dennis Ferruzzi
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Airflow 3's Deadline Alerts let you set "need-by" times on DAGs and fire callbacks when deadlines are missed. The built-in references cover common cases, but the real power is the feature's extensibility. In this workshop, led by the feature's author, we will go beyond the basics and explore these more advanced features.

We start with an overview of how DeadlineAlert, DeadlineReference, and Callback fit together, and how the scheduler detects misses. Then, a guided project: coding our own Callback implementation and building custom DeadlineReference classes using the @deadline_reference decorator, implementing _evaluate_with(), serialization, and required_kwargs. We wrap up with a hackathon-style "competition" to build the most creative WORKING DeadlineReference (business hours, the last time it didn't rain in Vancouver, the moon phases, the last time the Leafs won the cup... anything goes, as long as it serializes and returns a valid datetime).

BONUS! Your hackathon "projects" would make a great lightning talk topic!

Submission reviewer note: OR a 25 minute talk. Architecture overview and live demo with the rest as a github link, but the workshop format would be more engaging.