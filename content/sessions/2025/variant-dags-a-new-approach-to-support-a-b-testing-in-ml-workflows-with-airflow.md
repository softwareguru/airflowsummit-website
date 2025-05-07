---
title: "Variant DAGs: A new approach to support A/B testing in ML workflows with Airflow"
slug: variant-dags-a-new-approach-to-support-a-b-testing-in-ml-workflows-with-airflow
speakers:
 - Shlomi Chovel
topics:
 - Use cases
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Our team at Amazon's P13n faced a challenge: how to create experimental variants of ML workflows for A/B testing product recommendations on the website without sacrificing speed or resources. The solution we developed addresses this challenge while disrupting the conventional Airflow practices.
Airflow documentation advises:
"Never delete a task from a DAG.. It is advised to create a new DAG in case the tasks need to be deleted."
We offer an alternative perspective: by carefully modifying existing DAGs to create experimental variants, we've achieved a balance between code reuse and experiment isolation. Features:
1. Create variant DAGs by selectively modifying tasks and dependencies
2. Easily specify where variant workflows should diverge from the original
3. Automatic data dependency management using external task sensors
4. Synchronization with Amazon's internal spark job solution we use to run big data workloads from Airflow

This approach reduced development time and resource usage for our team while maintaining the integrity of our experimental process. In this session, we'll explore our implementation and share real-world examples.