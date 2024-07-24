---
title: "Resume"
date: 2023-07-19
draft: false
---

[Check out my GitHub for more projects and details!](https://github.com/P101010)

## Projects Table of Contents
1. [Brain Tumor Classification – Deployment ready project](#brain-tumor-classification--deployment-ready-project)
2. [Body Composition Scanner](#body-composition-scanner)
3. [Room Occupancy Estimation](#room-occupancy-estimation)
4. [Health Centre Database and Datawarehouse for Analysis](#health-centre-database-and-datawarehouse-for-analysis)
5. [MBTA – Machine learning model for predicting the load on bus](#mbta--machine-learning-model-for-predicting-the-load-on-bus)
6. [European Football/Soccer Database Management System](#european-footballsoccer-database-management-system)
7. [Timeseries Analysis of Human Activities](#timeseries-analysis-of-human-activities)
8. [Formula1 – Battle for the Drivers’ Championship Analysis and Dashboard](#formula1--battle-for-the-drivers-championship-analysis-and-dashboard)

## Projects

### Brain Tumor Classification – Deployment ready project

![Brain Tumor Classification Image](/images/BTC.png)  
- Implemented CI/CD using **Git Actions**, created the latest Docker image and stored it in **GCP artifact registry**.
- **Kubernetes** picked this Docker image and hosted it on one of the pods in the cluster.
- Used **FastAPI** for backend endpoint communication and **Streamlit** for the frontend application.
- Implemented data versioning using **DVC**, model versioning and tracking using **MLFlow**, and automated model training and retraining pipelines using **Airflow DAGs**.
- Designed a monitoring dashboard from parsed logs to identify data drift, data skew, and model confidence.

### Body Composition Scanner

![Body Composition Scanner Image](/images/project.png)  
- Used a pretrained Resnet model to extract silhouettes of front and left or right facing images of subjects.
- Extracted features from silhouettes such as area, solidity of contour.
- Established a linear relation between wrist size and neck circumference through a paper by Prof. John Verzani called "Human Proportions," which was later used for other component calculations like fat percentage, lean mass, and more.

### Room Occupancy Estimation

- Developed machine learning algorithms such as **Linear Regression**, **LDA**, **QDA**, and **SVM** for multi-class classification of predicting occupancy using **NumPy**, **Pandas**, and **Scipy**.
- Applied techniques such as square root, cube root, logarithmic transformations to ensure data follows a normal distribution and leveraged SMOTE to generate synthetic data and achieve a balanced dataset across all classes.

### Health Centre Database and Datawarehouse for Analysis

![Health Centre Database Image](/images/DW.png)  
- Designed and modeled a database to handle various aspects involved in a healthcare center.
- Created a multidimensional model with several facts such as Consultation, Tests Conducted, and Operations performed to analyze health center metrics and identify potential hazards.
- Implemented OLTP and OLAP databases using **PostgreSQL** and used **Talend Jobs** for ETL operations.

### MBTA – Machine learning model for predicting the load on bus

- Trained supervised machine learning models like **Linear Regression**, **KNN**, **Random Forest**, and **Decision Trees** using **Scikit-learn** on MBTA data to predict bus load.
- Identified **Random Forest** as the most accurate model with 82% accuracy, improving to 84.8% with further tuning of hyperparameters.

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
