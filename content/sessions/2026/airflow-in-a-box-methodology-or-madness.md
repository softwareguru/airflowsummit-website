---
title: "Airflow in a Box: Methodology or Madness?"
slug: airflow-in-a-box-methodology-or-madness
speakers:
 - Nicholas Redd
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Airflow testing today is a patchwork: you can validate code and catch obvious breakage early, but many production failures live in the seams—runtime state, persistence, serialization boundaries, API behavior, and the way a real deployment executes work across components. The fast tools are valuable, yet they don’t fully model Airflow as a system. Meanwhile, the default development posture nudges you toward single-process behavior and away from realistic concurrency and state interactions. The result is a familiar trade: quick feedback vs. meaningful confidence. “Airflow in a Box” is a step toward collapsing that trade—making deeper, more production-relevant tests accessible without requiring a full, heavyweight instance for every iteration. In this talk, we’ll discuss methodology, quantify slickness, and share real code! 