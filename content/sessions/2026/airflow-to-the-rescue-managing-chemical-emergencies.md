---
title: "Airflow to the rescue: managing chemical emergencies"
slug: airflow-to-the-rescue-managing-chemical-emergencies
speakers:
 - Eloi Codina Torras
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

At Meteosim, Airflow is the engine for our entire decision system. It runs daily weather and air quality forecasts on schedule, but it also enables OnaChem React, a software that lets users manage chemical emergencies in real-time, and helps us manage consultancy projects.

This talk covers how we set up Airflow 3 to handle five very different types of workloads:

    1. Daily Forecasts: Running physics simulations for weather and air quality.

    2. Sensor Validation: Ingest data from thousands of sensors and validate it.

    3. Human-in-the-Loop: Managing long-running consultancy projects where Dags pause and wait for expert approval.

    4. Emergency Response: Help users manage chemical emergencies using multiple real-time toxic dispersion simulations with pre-defined workflows through our SaaS platform.

    5. Training AI models: Track multiple experiments.

We will explain why Airflow 3 was necessary to make this work. You will see how we orchestrate physics, AI, and human decisions in a single environment.