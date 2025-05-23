---
title: "Gen AI using Airflow 3: A vision for Airflow RAGs"
slug: gen-ai-using-airflow-3-a-vision-for-airflow-rags
speakers:
 - Kaxil Naik
 - Ash Berlin-Taylor
time_start: 2024-09-12 11:30:00
time_end: 2024-09-12 12:15:00
room: Elizabethan A+B
track: New features
day: 20243
timeslot: 91
gridarea: "6/4/8/5"
images: 
 - /images/sessions/2024/genai-airflow-rags.jpg
slides: 2024/83-Gen-AI-using-Airflow-3.pdf
video: https://youtu.be/0djdrF91n5s
---

Gen AI has taken the computing world by storm. As Enterprises and Startups have started to experiment with LLM applications, it has become clear that providing the right context to these LLM applications is critical. 
 
 
This process known as Retrieval augmented generation (RAG) relies on adding custom data to the large language model, so that the efficacy of the response can be improved. Processing custom data and integrating with Enterprise applications is a strength of Apache Airflow. 
 
This talk goes into details about a vision to enhance Apache Airflow to more intuitively support RAG, with additional capabilities and patterns. Specifically, these include the following
 
 
 
 - Support for unstructured data sources such as Text, but also extending to Image, Audio, Video, and Custom sensor data
 
 - LLM model invocation, including both external model services through APIs and local models using container invocation. 
 
 - Automatic Index Refreshing with a focus on unstructured data lifecycle management to avoid cumbersome and expensive index creation on Vector databases
 
 - Templates for hallucination reduction via testing and scoping strategies
