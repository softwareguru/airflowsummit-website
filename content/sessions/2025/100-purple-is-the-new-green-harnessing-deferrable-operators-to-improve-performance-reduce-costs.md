---
title: "Purple is the new green: harnessing deferrable operators to improve performance & reduce costs"
slug: purple-is-the-new-green-harnessing-deferrable-operators-to-improve-performance-reduce-costs
speakers:
 - Ethan Shalev
topics:
 - Use cases
time_start: 2025-10-08 16:15:00
time_end: 2025-10-08 16:40:00
room: Columbia D
track: Use cases
day: 20252
timeslot: 100
gridarea: 14/4/15/5
slides:
video: https://youtu.be/vqH6dsPPlgw
images:
 - /images/sessions/2025/purple-is-the-new-green.png
---

Airflow’s traditional execution model often leads to wasted resources: worker nodes sitting idle, waiting on external systems. At Wix, we tackled this inefficiency head-on by refactoring our in-house operators to support Airflow’s deferrable execution model.

Join us on a walk through Wix’s journey to a more efficient Airflow setup, from identifying bottlenecks to implementing deferrable operators and reaping their benefits. We’ll share the alternatives considered, the refactoring process, and how the team seamlessly integrated deferrable execution with no disruption to data engineers’ workflows.

Attendees will get a practical introduction to deferrable operators: how they work, what they require, and how to implement them. We’ll also discuss the changes made to Wix’s Airflow environment, the process of prioritizing operators for modification, and lessons learned from testing and rollout.

By the end of this talk, attendees will be ready to embrace more purple tasks in their Airflow UI, boosting efficiency, cutting costs, and making their workflows greener in every other way.
