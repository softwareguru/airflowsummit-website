---
title: "Automating Threat Intelligence with Airflow, XDR, and LLMs using the MITRE ATT&CK Framework"
slug: automating-threat-intelligence-with-airflow-xdr-and-llms-using-the-mitre-att-ck-framework
speakers:
 - Karan Alang
topics:
 - Airflow & ...
track: Airflow & ...
time_start: 2025-10-16 17:30:00
time_end: 2025-10-16 18:00:00
room: Online
day: 20255
timeslot: 16
gridarea: 8/2/9/3
slides:
video: https://youtu.be/K5EDFthOAyg
images:
 - /images/sessions/2025/automating-threat-intelligence-with-airflow-xdr-and-llms-using-the-mitre-att-ck-framework.png
draft: false
---

Security teams often face alert fatigue from massive volumes of raw log data. This session demonstrates how to combine Apache Airflow, XDR, and LLMs to build automated pipelines for smarter threat triage—grounded in the MITRE ATT&CK framework.

We’ll explore how Airflow can orchestrate a full workflow: ingesting XDR alerts, using LLMs to summarize log events, matching behavior to ATT&CK tactics and techniques, and generating enriched incident summaries. With AI-powered interpretation layered on top of structured threat intelligence, teams can reduce manual effort while increasing context and clarity.

You’ll learn how to build modular DAGs that automate: 

* Parsing and routing XDR alerts, 
* Querying LLMs for human-readable summaries, 
* Mapping IOCs to ATT&CK using vector similarity or prompt templates, 
* Outputting structured threat reports for analysts.

The session includes a Case study integrating open-source tools and public ATT&CK data, and will provide reusable components for rapid adoption. If you’re a SecOps engineer or ML practitioner in cybersecurity, this talk gives you a practical blueprint to deploy intelligent, scalable threat automation.