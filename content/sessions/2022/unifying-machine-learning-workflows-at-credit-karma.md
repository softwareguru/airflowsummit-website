---
id: 
title: "Vega: Unifying Machine Learning Workflows at Credit Karma using Apache Airflow"
url: /sessions/2022/unifying-machine-learning-workflows-at-credit-karma
speakers:
 - Debasish Das
block: 
slot: 
track: Productionizing ML
time_start: 2022-01-01T17:00:00.000Z
time_end: 2022-01-01T18:00:00.000Z

---

At Credit Karma, we enable financial progress for more than 100 million of our members by recommending them personalized financial products when they interact with our application. In this talk we are introducing our machine learning platform to build interactive and production model-building workflows to serve relevant financial products to Credit Karma users.
 
Vega, Credit Karma’s Machine Learning Platform, has 3 major components: 1) QueryProcessor for feature and training data generation, backed by Google BigQuery, 2) PipelineProcessor for feature transformations, offline scoring and model-analysis, backed by Apache Beam 3) ModelProcessor for running Tensorflow and Scikit models, backed by Google AI Platform, which provides data scientists the flexibility to explore different kinds of machine learning or deep learning models, ranging from gradient boosted trees to neural network with complex structures  
 
Vega exposed a unified Python API for Feature Generation, Modeling ETL, Model Training and Model Analysis. Vega supports writing interactive notebooks and python scripts to run these components in local mode with sampled data and in cloud mode for large scale distributed computing. Vega provides the ability to chain the processors provided by data scientists through Python code to define the entire workflow. Then it automatically generates the execution plan for deploying the workflow on Apache Airflow for running offline model experiments and refreshes. Overall, with the unified python API and automated Airflow DAG generation, Vega has improved the efficiency of ML Engineering. Using Airflow we deploy more than 20K features and 100 models daily