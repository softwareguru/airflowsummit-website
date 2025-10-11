---
title: "Vayu: The Airflow Copilot"
slug: vayu-airflow-copilot
speakers:
 - Muhammed Irshad
 - Sanchit Sreekanth
topics:
 - Community

time_start: 2025-10-16 14:30:00
time_end: 2025-10-16 15:00:00
room: Online
track: Use cases
day: 20255
timeslot: 10
gridarea: 2/2/3/3

slides:
video:

---

Vayu is a conversational copilot for Apache Airflow, developed at Prevalent AI to help data engineers manage, troubleshoot, and fix pipelines using natural language. Deployments often fail silently due to misconfigurations, missing connections, or runtime issues impossible to identify in unit tests. Vayu tackles these via a troubleshooting agent that inspects logs, metrics, configs, and runtime state to find root causes and suggest fixes saving engineers significant troubleshooting time. It can also apply approved fixes to DAG code and commit them to your version control system.

Key Capabilities:
 * Troubleshooting Agent: Inspects logs, configs, variables, and connections to find root causes and suggest fixes.
 * Pipeline Mechanic Agent: Suggests code-level fixes e.g., missing connections or bad imports and, once approved, commits them to version control.
 * DAG Manager Agent: Understands DAG logic, suggests improvements, and can trigger DAGs conversationally.

Architecture: Built with open-source tools including Google ADK as the orchestration layer and a custom Airflow MCP server based on the FastMCP framework. LLMs never access Airflow directly. The full codebase will be open-sourced.