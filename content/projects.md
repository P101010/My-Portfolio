---
title: "Projects"
date: 2023-07-19
draft: false
---

[Check out my GitHub for more details!](https://github.com/P101010)

## Projects

### Brain Tumor Classification – Deployment ready project

![Brain Tumor Classification Image](/images/BTC.png)  
- Developed a brain-tumor classifier using CNN and managed versioning and artifacts of model using MLFlow.
- Automated training and retraining of model using Airflow DAG’s based on feedback received.
- Deployed a scalable application developed using Streamlit leveraging Restful API endpoints on Kubernetes, based on the latest Docker image in the artifact registry, pushed by GitHub Actions on change thereby achieving CI/CD.
- Monitored model for confidence and prediction distribution, data for drift and skew to increase lifecycle of model.

### RAG Database Assistant

![RAG Database Assistant Image](/images/RAG.png)  
- Enabled users to query and retrieve results from the database in a conversational format leveraging GPT-4o on Langchain.
- Reduced prompt size by retrieving relevant schemas based on user queries by doing a semantic search on a vector database.
- Enhanced SQL query accuracy by adding few shot examples relevant to user queries and employing conversational memory.

### Multimodal Document Handling

![Multimodal Document Handling Image](/images/ColPali.png)  
- Retrieved relevant document pages based on user queries by converting images of pdf documents into embeddings using a vison transformer, storing them in a vector database and doing a similarity search on embeddings of user queries.
- Optimized storage in database by using binary quantization and enhanced search accuracy by reranking and oversampling.

### Body Composition Scanner

![Body Composition Scanner Image](/images/project.png)  
- Used a pretrained Resnet model to extract silhouettes of front and left or right facing images of subjects.
- Extracted features from silhouettes such as area, solidity of contour.
- Established a linear relation between wrist size and neck circumference through a paper by Prof. John Verzani called "Human Proportions," which was later used for other component calculations like fat percentage, lean mass, and more.


### Penalty Analysis and Prediction

![Penalty Analysis and Prediction Image](/images/HK.png)  
 
- Created a new dataset with paramters such as isFansSide and established thaere exists a complex realtionship between them and direction of penalty for one test player Harry Kane
- Applied various ML tecniques and settled on distance based KNN moedel which when tuned to 5 neighbours achieved an accuracy of 78%. 
- You can find a Google sheet of all the 1234 possible scenarios my model could face and the prediction in the read me of my GitHub repo.

### Classical Machine Learning Algorithms

- Implemented classical machine learning algorithms (Linear Regression, Logistic Regression, and SVM) from scratch using Python, NumPy, and SciPy, demonstrating strong foundational understanding of model optimization, regularization, gradient descent.
- Developed comprehensive evaluation metrics (Accuracy, RMSE, SSE, Precision, Recall) to assess model performance, improving the interpretability and robustness of predictions.

### F1 2021 – Visual Storyboard and Analytical Dashboard

![Formula1 Analysis Image](/images/Dashboard.png)  
- Crafted a data-driven story showcasing the season’s pivotal moments and dynamics, allowing audience to grasp complex factors such as race strategies, driver performance and points progression that contributed to the championship battle.
- Designed an interactive dashboard on Tableau featuring key insights into driver performance and championship progression.

### Health Centre Database and Datawarehouse for Analysis

![Health Centre Database Image](/images/DW.png)  
- Designed a multidimensional model for tracking metrics with a focus on identifying diagnostic trends and regional hazards.
- Utilized AWS Glue jobs for ETL from PostgreSQL to Redshift, leveraging S3 buckets for intermediate storage and Lambda functions to automate job triggers for efficient data processing.


### MBTA – Machine learning model for predicting the load on bus

- Improved user satisfaction by reducing load on bus by 30% with scheduling strategies derived based on a random forest model developed with MBTA Data Science team which achieved an accuracy of 84.8%.

### European Football/Soccer Database Management System

![European Football Database Image](/images/DMA.png)  
- Architected and implemented a scalable and robust database system for the European football/soccer league using **MySQL** and **MongoDB**.
- Integrated **MySQL database** with **Python** using **SQLAlchemy** for data analysis.

### Timeseries Analysis of Human Activities

- Conducted timeseries analysis on human activity data, applying techniques such as **ARIMA**, **LSTM**, and **Prophet** models to forecast and understand patterns.

[Check out my GitHub for more projects and details!](https://github.com/P101010)
