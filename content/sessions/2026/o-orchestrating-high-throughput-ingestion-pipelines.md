---
title: "Orchestrating High-Throughput Ingestion Pipelines: Airflow Meets Apache Beam"
url: onlinereconnect/orchestrating-high-throughput-ingestion-pipelines
speakers:
 - Ashwin Sampathkumar
track: Data & AI Applications
room: Online
#day: 2026o1
time_start: 2026-11-04 15:00:00
time_end: 2026-11-04 15:30:00
timeslot: 
gridarea: 
images: 

slides:
video: 
---

Building a RAG prototype is easy, but keeping millions of enterprise documents continually parsed, chunked, embedded, and indexed in vector databases is hard. Document updates, schema changes, embedding model versioning, and rate limits on embedding APIs create unique engineering hurdles.

In this talk, we present a robust, scalable architecture combining Apache Airflow and Apache Beam on Dataflow for production RAG pipelines. We demonstrate how Airflow schedules and triggers incremental document ingestion, how Beam parallelizes document chunking and embedding generation via batch inference transforms, and how the pipeline safely handles upserts, and embedding version migrations. Attendees will gain a blueprint for building highly scalable, cost-effective vector ingestion pipelines.