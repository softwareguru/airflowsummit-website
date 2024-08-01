---
title: "Airflow, Spark, and LLMs: Turbocharging MLOps at ASAPP"
speakers:
 - Udit Saxena
track:
 - Use cases
images:
 - /images/sessions/2024/airflow-spark-llms.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

This talk will explore ASAPP's use of Apache Airflow to streamline and optimize our machine learning operations (MLOps). 

Key highlights include:
 - Integrating with our custom Spark solution for achieving speedup, efficiency, and cost gains for generative AI transcription, summarization and intent categorization pipelines
 - Different design patterns of integrating with efficient LLM servers - like TGI/vllm/tensor-RT for Summarization pipelines with/without Spark.
 - An overview of batched LLM inference using Airflow as opposed to real time inference outside of it
 - [Tentative] Possible extension of this scaffolding to Reinforcement Learning from Human Feedback (RLHF) and Reinforcement Learning from AI Feedback (RLAIF) for fine-tuning LLMs, using Airflow as the orchestrator.

Additionally, the talk will cover ASAPP's MLOps journey with Airflow over the past few years, including an overview of our cloud infrastructure, various data backends, and sources.

The primary focus will be on the machine learning workflows at ASAPP, rather than the data workflows, providing a detailed look at how Airflow enhances our MLOps processes.