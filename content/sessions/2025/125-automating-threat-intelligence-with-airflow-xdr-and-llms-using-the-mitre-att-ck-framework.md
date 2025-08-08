---
title: "Automating Threat Intelligence with Airflow, XDR, and LLMs using the MITRE ATT&CK Framework"
slug: automating-threat-intelligence-with-airflow-xdr-and-llms-using-the-mitre-att-ck-framework
speakers:
 - Karan Alang
topics:
 - Airflow & ...
time_start: 2025-10-09 11:00:00
time_end: 2025-10-09 11:25:00
room: Beckler
track: Airflow & ...
day: 20253
timeslot: 125
gridarea: 5/5/6/6
slides:
video:
---

Security teams often face alert fatigue from massive volumes of raw log data. This session demonstrates how to combine Apache Airflow, Wazuh, and LLMs to build automated pipelines for smarter threat triage—grounded in the MITRE ATT&CK framework.

We’ll explore how Airflow can orchestrate a full workflow: ingesting Wazuh alerts, using LLMs to summarize log events, matching behavior to ATT&CK tactics and techniques, and generating enriched incident summaries. With AI-powered interpretation layered on top of structured threat intelligence, teams can reduce manual effort while increasing context and clarity.

You’ll learn how to build modular DAGs that automate:
	•	Parsing and routing Wazuh alerts,
	•	Querying LLMs for human-readable summaries,
	•	Mapping IOCs to ATT&CK using vector similarity or prompt templates,
	•	Outputting structured threat reports for analysts.

The session includes a real-world example integrating open-source tools and public ATT&CK data, and will provide reusable components for rapid adoption. If you’re a SecOps engineer or ML practitioner in cybersecurity, this talk gives you a practical blueprint to deploy intelligent, scalable threat automation.