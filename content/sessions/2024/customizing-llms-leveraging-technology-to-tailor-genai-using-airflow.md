---
title: "Customizing LLMs: Leveraging Technology to tailor GenAI using Airflow"
slug: customizing-llms-leveraging-technology-to-tailor-genai-using-airflow
speakers:
 - Vincent La
track:
 - Use cases
images:
 - /images/sessions/2024/customizing-llm.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Laurel provides an AI-driven timekeeping solution tailored for accounting and legal firms, automating timesheet creation by capturing digital work activities. This session highlights two notable AI projects:
1. UTBMS Code Prediction: Leveraging small language models, this system builds new embeddings to predict work codes for legal bills with high accuracy. More details are available in our case study: https://www.laurel.ai/resources-post/enhancing-legal-and-accounting-workflows-with-ai-insights-into-work-code-prediction.
2. Bill Creation and Narrative Generation: Utilizing Retrieval-Augmented Generation (RAG), this approach transforms users' digital activities into fully billable entries.

Additionally, we will discuss how we use Airflow for model management in these AI projects:
- Daily Model Retraining: We retrain our models daily
- Model (Re)deployment: Our Airflow DAG evaluates model performance, redeploying it if improvements are detected
- Cost Management: To avoid high costs associated with querying large language models frequently, our DAG utilizes RAG to efficiently summarize daily activities into a billable timesheet at day's end.  