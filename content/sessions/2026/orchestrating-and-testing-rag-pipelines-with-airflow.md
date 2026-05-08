---
title: "Orchestrating and Testing RAG Pipelines with Airflow"
slug: orchestrating-and-testing-rag-pipelines-with-airflow
speakers:
 - Shrividya Hegde
topics:
 - Data & AI Applications
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

RAG pipelines fail silently. Bad retrievals, hallucinated answers, and stale vectors rarely trigger alerts; they quietly degrade your AI product.
This session presents a reference DAG architecture for production-grade RAG ingestion built on Airflow 3, with inline quality gates that evaluate retrieval accuracy and LLM faithfulness before a single vector reaches production. We'll walk through four common RAG failure modes and the specific Airflow pattern that stops each one using RAGAS as the evaluation framework, and Airflow 3's TaskFlow API, Assets, and DAG Versioning to make pipelines reproducible and event-driven.
You'll leave with reusable quality gate patterns and a concrete architecture you can adapt — because in RAG systems, quality shouldn't be an afterthought. It should be built into the pipeline from the start.