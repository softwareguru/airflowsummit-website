---
title: "LLM-Powered Review Analysis: Optimising Data Engineering using Airflow"
slug: llm-powered-review-analysis
speakers:
 - Naseem Shah
time_start: 2025-10-07 16:45:00
time_end: 2025-10-07 17:10:00
room: Columbia D
track: Use cases
day: 20251
timeslot: 36
gridarea: 13/4/14/5 
slides:
video: 
---

A real-world journey of how my small team at Xena Intelligence built robust data pipelines for our enterprise customers using Airflow. If you’re a data engineer, or part of a small team, this talk is for you. Learn how we orchestrated a complex workflow to process millions of public reviews.

What You’ll Learn:

1. Cost-Efficient DAG Designing: Decomposing complex processes into atomic tasks using the TaskFlow, XComs, Mapped tasks, and Task groups. Diving into one of our DAGs as a concrete example of how our approach optimizes parallelism, error handling, delivery speed, and reliability.

2. Integrating LLM Analysis: Explore how we integrated LLM-based analysis into our pipeline. Learn how we designed the database, queries, and ingestion to Postgres.

3. Extending Airflow UI: We developed a custom Airflow UI plugin that filters and visualizes DAG runs by customer, product, and marketplace, delivering clear insights for faster troubleshooting.

4. Leveraging Airflow REST API: Discover how we leveraged the API to trigger DAGs on demand, elevating the UX by tracking mapped DAG progress and computing ETAs.

5. CI/CD and Cost Management: Get practical tips for deploying DAGs with CI/CD.