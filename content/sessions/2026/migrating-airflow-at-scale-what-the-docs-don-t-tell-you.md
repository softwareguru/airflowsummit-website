---
title: "Migrating Airflow at Scale - What the Docs Don't Tell You"
slug: migrating-airflow-at-scale-what-the-docs-don-t-tell-you
speakers:
 - Olivier Daneau
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

If you are migrating from self-hosted Airflow to any of the managed platforms, most migration guides you'll find online assume one environment, one team, one version. Large organizations are never that simple.

This talk comes from four years of assisting customers with real migrations across some of the biggest Airflow deployments out there, from self-hosted open source to managed cloud platforms like MWAA, GCC, and Astro, and between major version upgrades. 

The organizations we worked with had multiple teams, multiple Airflow versions running in parallel, and years of decisions baked into their infrastructure and Dags.

We'll walk through what a migration actually looks like at that scale. The architecture, design, and planning work that has to happen before anyone touches a Dag, and the organizational coordination needed to make it work.

We'll cover every topic so that you leave this session ready to confidently start your migration projects.
You'll leave with a framework for scoping a migration, a clearer picture of the work to come, and lessons we learned from doing this across organizations that couldn't afford to get it wrong.