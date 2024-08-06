---
title: "Managing version upgrades without feelings of terror"
slug: managing-version-upgrades-without-feelings-of-terror
speakers:
 - Daniel Standish
time_start: 2024-09-10 14:35:00
time_end: 2024-09-10 15:00:00
room: Elizabethan A+B
track: Airflow Intro talks
day: 20241
timeslot: 20
gridarea: "9/4/10/5"
images: 
 - /images/sessions/2024/managing-version-upgrades.jpg
---

Airflow version upgrades can be challenging. Maybe you upgrade and your dags fail to parse (that’s an easy fix). Or maybe you upgrade and everything looks fine, but when your dag runs, you can no longer connect to mysql because the TLS version changed. In this talk I will provide concrete strategies that users can put into practice to make version upgrades safer and less painful. Topics may include:
 
  * What semver means and what it implies for the upgrade process
 
  * Using integration test dags, unit tests, and a test cluster to smoke out problems
 
  * Strategies around constraints files / pinning, and managing providers vs core versions
 
  * Using `db clean` prior to upgrade to reduce table size
 
  * Rollback strategies
 
  * What to do about warnings (e.g. deprecation warnings)?
 
 
 
 I’ll also focus on keeping it simple. Sometimes things like “integration tests” and “CI” can be scary for people. Even without having set up anything automated, there are still things you can do to make management of upgrades a little less painful and risky.