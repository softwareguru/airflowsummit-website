---
title: "Safe Airflow Upgrades with LLM Guardians: Automating Version Migration and Error Prevention"
slug: safe-upgrades
speakers:
 - Azhar Izzannada Elbachtiar
time_start: 2025-10-16 17:30:00
time_end: 2025-10-16 18:00:00
room: Online
track: Best practices
day: 20255
timeslot: 16
gridarea: 8/2/9/3
images: 
slides:
video:
---

Upgrading Airflow can be challenging, small change may trigger pipeline failures and long fixing. This session presents solution that simplifies migrations across multiple Airflow releases version by automate analyzing code repositories, change notes, best practices, and other essential documentation using LLM Guardian that identifies potential issues. It scans DAGs and dependency to predict incompatibilities, and generate fixes (e.g., deprecated operator replacements).

You'll see how the system scans DAG for hidden risks, auto-generates targeted code patches, and post-migration to verify stability and performance. The Demo will highlight rapid, error-free transitions even for legacy systems using backward-compatible code adjustments and rollback plans. Imagine an upgrade that took months into just a couple of hours while reducing risk and keep your environment secure.

Key takeaways:
- Intelligent Analysis: Cross-references changelogs, GitHub histories, and provider packages to flag risks.
- Precision Fixes: Updates syntax, dependencies, and configurations while preserving workflows.
- Confidence Building: Generates audit-ready reports and dry-run results to justify upgrades.