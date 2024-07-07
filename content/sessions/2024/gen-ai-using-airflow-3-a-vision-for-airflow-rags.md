---
title: "Gen AI using Airflow 3: A vision for Airflow RAGs"
slug: gen-ai-using-airflow-3-a-vision-for-airflow-rags
speakers:
 - Vikram Koka
 - Kaxil Naik
 - Ash Berlin-Taylor
track:
 - New features
images:
 - /images/sessions/2024/gen-ai.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Gen AI has taken the computing world by storm. As Enterprises and Startups have started to experiment with LLM applications, it has become clear that providing the right context to these LLM applications is critical. 

This process known as Retrieval augmented generation (RAG) relies on adding custom data to the large language model, so that the efficacy of the response can be improved. Processing custom data and integrating with Enterprise applications is a strength of Apache Airflow. 

This talk goes into details about a vision to enhance Apache Airflow to more intuitively support RAG, with additional capabilities and patterns. Specifically, these include the following

- Support for unstructured data sources such as Text, but also 
  extending to Image, Audio, Video, and Custom sensor data
- LLM model invocation, including both external model services 
  through APIs and local models using container invocation. 
- Automatic Index Refreshing with a focus on unstructured data 
  lifecycle management to avoid cumbersome and expensive 
  index creation on Vector databases
- Templates for hallucination reduction via testing and scoping 
  strategies