---
title: "Self-Healing Airflow: Pipelines That Fix Themselves"
slug: self-healing-airflow-pipelines-that-fix-themselves
speakers:
 - Shrividya Hegde
track: Builder
room: Online
day: 2026o2
time_start: 2026-11-05 14:00:00
time_end: 2026-11-05 14:30:00
timeslot: 7
gridarea: 8/2/9/8
slides: 
video:
---

It's 2 AM and a task just failed. Does someone get paged, or does the pipeline quietly diagnose the problem, wait the right amount of time, retry, and only escalate when it truly can't recover on its own?

Most Airflow pipelines are babysat. This session shows how to make them self-healing instead. We'll work up from the 80% fix , retries with exponential back off ,through failure and retry callbacks, SLA monitoring, automatic clearing of stuck and zombie tasks, and circuit breakers that stop hammering a broken downstream system. You'll see how to route alerts to Slack or PagerDuty so humans are interrupted only when it matters, and how to keep secrets out of your DAGs while doing it.

Coming from a testing background, I'll frame this the way an SRE would: design for failure first. You'll leave with concrete patterns and a template you can drop into your own DAGs on Monday.