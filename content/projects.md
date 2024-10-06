---
title: "Projects"
date: 2023-07-19
draft: false
---

[Check out my GitHub for more projects and details!](https://github.com/P101010)


## Projects Table of Contents
1. [Brain Tumor Classification – Deployment ready project](#brain-tumor-classification--deployment-ready-project)
2. [Body Composition Scanner](#body-composition-scanner)
3. [Penalty Analysis and Prediction](#penalty-analysis-and-prediction)
4. [Room Occupancy Estimation](#room-occupancy-estimation)
5. [Health Centre Database and Datawarehouse for Analysis](#health-centre-database-and-datawarehouse-for-analysis)
6. [MBTA – Machine learning model for predicting the load on bus](#mbta--machine-learning-model-for-predicting-the-load-on-bus)
7. [European Football/Soccer Database Management System](#european-footballsoccer-database-management-system)
8. [Timeseries Analysis of Human Activities](#timeseries-analysis-of-human-activities)
9. [Formula1 – Battle for the Drivers’ Championship Analysis and Dashboard](#formula1--battle-for-the-drivers-championship-analysis-and-dashboard)

## Projects

### Brain Tumor Classification – Deployment ready project

![Brain Tumor Classification Image](/images/BTC.png)  
- Developed a brain-tumor classifier using CNN and managed versioning and artifacts of model using MLFlow.
- Automated training and retraining of model using Airflow DAG’s based on feedback received.
- Deployed a scalable application developed using Streamlit leveraging Restful API endpoints on Kubernetes, based on the latest Docker image in the artifact registry, pushed by GitHub Actions on change thereby achieving CI/CD.
- Monitored model for confidence and prediction distribution, data for drift and skew to increase lifecycle of model.

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

### Health Centre Database and Datawarehouse for Analysis

![Health Centre Database Image](/images/DW.png)  
- Designed and modeled a database to handle various aspects involved in a healthcare center.
- Created a multidimensional model with several facts such as Consultation, Tests Conducted, and Operations performed to analyze health center metrics and identify potential hazards.
- Implemented OLTP and OLAP databases using **PostgreSQL** and used **Talend Jobs** for ETL operations.

### MBTA – Machine learning model for predicting the load on bus

- Improved user satisfaction by reducing load on bus by 30% with scheduling strategies derived based on a random forest model developed with MBTA Data Science team which achieved an accuracy of 84.8%.

### European Football/Soccer Database Management System

![European Football Database Image](/images/DMA.png)  
- Architected and implemented a scalable and robust database system for the European football/soccer league using **MySQL** and **MongoDB**.
- Integrated **MySQL database** with **Python** using **SQLAlchemy** for data analysis.

### Timeseries Analysis of Human Activities

- Conducted timeseries analysis on human activity data, applying techniques such as **ARIMA**, **LSTM**, and **Prophet** models to forecast and understand patterns.

### Formula1 – Battle for the Drivers’ Championship Analysis and Dashboard

![Formula1 Analysis Image](/images/Dashboard.png)  
- Extracted and integrated data from various sources and APIs, utilized **Python** for data wrangling, and created a comprehensive dashboard displaying the 2021 season insights using **Tableau**.
- Used **Exploratory Data Analysis** techniques to uncover factors influencing the 2021 championship battle.

[Check out my GitHub for more projects and details!](https://github.com/P101010)
