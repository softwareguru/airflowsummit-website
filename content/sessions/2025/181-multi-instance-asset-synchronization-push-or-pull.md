---
title: "Multi-Instance Asset Synchronization - push or pull?"
slug: multi-instance-asset-synchronization-push-or-pull
speakers:
 - Sebastien Crocquevieille
topics:
 - Use cases
time_start: 2025-10-09 16:15:00
time_end: 2025-10-09 16:40:00
room: Columbia C
track: Use cases
day: 20253
timeslot: 181
gridarea: 16/3/17/4
slides:
video: https://youtu.be/QP_b60bKlFs
images:
 - images/sessions/2025/multi-instance-asset-synchronization.png
---

As Data Engineers, our jobs regularly include scheduling or scaling workflows.

But have you ever asked yourself, can I scale my scheduling ?

It turns out that you can!
But doing so raises a number of issues that need to be addressed.

In this talk we'll be:
- Recapping Asset-aware scheduling in Apache Airflow
- Discussing diverse methods to upscale our scheduling
- Solving the issue of maintaining our Airflow Asset synchronized between instances
- Comparing our professional push based solution and the built-in solution from [AIP-82](https://cwiki.apache.org/confluence/display/AIRFLOW/AIP-82+External+event+driven+scheduling+in+Airflow) and the pros and cons of each method.

I hope you will enjoy it!