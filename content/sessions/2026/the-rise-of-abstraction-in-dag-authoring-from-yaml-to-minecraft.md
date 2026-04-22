---
title: "The Rise of Abstraction in Dag Authoring: From YAML to Minecraft"
slug: the-rise-of-abstraction-in-dag-authoring-from-yaml-to-minecraft
speakers:
 - Volker Janz
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

In my almost 15 years as a data engineer, I've learned one universal truth: everyone needs orchestration. The marketing team needs daily attribution reports. The CRM team needs personalized newsletter triggers. The platform team needs cross-cloud data transfers. The analytics team needs third-party data imports. Data touches every corner of the business, and the orchestration layer is the one layer that connects it all.

This talk explores what becomes possible when we decouple pipeline logic (what happens) from definition (how it's authored). With the right abstractions, the authoring interface can be anything: Python, declarative YAML, templates, spreadsheets, or even a video game.

We will explore different levels of orchestration abstraction: native Python, declarative config (using the open-source project DAG Factory), templates (using the open-source project Blueprint), and AI-assisted Authoring. To prove the power of this decoupled architecture, I will showcase a custom Minecraft plugin that lets you build Airflow Dags by placing blocks in Minecraft (yes, you heard that right).