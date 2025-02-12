---
title: "Projects"
date: 2023-07-19
draft: false
---

[Check out my GitHub for more details!](https://github.com/P101010)

### Brain Tumor Classification – Deployment ready project

![Brain Tumor Classification Image](/images/BTC.png)  
- Deployed a scalable brain-tumor classifier on Kubernetes developed on Streamlit leveraging Restful API endpoints. 
- The deployment was based on the latest Docker image in the artifact registry, pushed by GitHub Actions achieving CI/CD.
- Developed the model using CNN on TensorFlow Keras and managed the versioning and artifacts using MLFlow.
- Automated training and retraining pipelines of model using Airflow DAGs based on triggers like feedback, model-decay.
- Monitored on Tableau the model for confidence, prediction distribution, data for drift, skew to increase lifecycle of model.

### MenuData chatbot challenege 

![MenuData chatbot challenege](/images/KG-Flow.jpg)  
- Implemented a chatbot with self-growing knowledge graph, updated with relevant external information based on interaction.
- Improved retrieval accuracy & latency by embedding external information in a topic-section-subsection format in vectorDB.
- For better experience used conversational memory, guardrails to filter out toxic language & ensure context aware interaction.
- Monitored execution workflows using LangSmith, to improve query efficiency and identifying bottlenecks in execution.


### Generative Models - VANs, GANs

![VAN Image](/images/VAE.png)  
- Designed and implemented Variational Autoencoders with a 32-dimensional latent space to reconstruct MNIST digits, enabling detailed exploration of latent space interpolations and smooth transitions between digit classes.
- Developed Generative Adversarial Networks with CNN based architectures for the generator and discriminator, optimizing adversarial training using binary cross-entropy loss to generate synthetic CIFAR-10 images.
- Implemented DeepSpeed's ZeRO optimization and mixed precision training with DDP to accelerate the training of the GAN framework, enabling the generation of high-quality images while reducing memory overhead and computational costs.

### RAG Database Assistant

![RAG Database Assistant Image](/images/RAG.png)  
- Enabled users to query and retrieve results from the database in a conversational format leveraging GPT-4o on Langchain.
- Reduced prompt size by retrieving relevant schemas based on user queries by doing a semantic search on a vector database.
- Enhanced SQL query accuracy by adding few shot examples relevant to user queries and employing conversational memory.

### Multimodal Document Handling

![Multimodal Document Handling Image](/images/ColPali.png)  
- Retrieved relevant document pages based on user queries by converting images of pdf documents into embeddings using a vison transformer, storing them in a vector database and doing a similarity search on embeddings of user queries.
- Optimized storage in database by using binary quantization and enhanced search accuracy by reranking and oversampling.

### MBTA – Machine learning model for predicting the load on bus

- Improved user satisfaction by reducing load on bus by 30% with scheduling strategies derived based on a random forest model developed with MBTA Data Science team which achieved an accuracy of 84.8%.

### Penalty Analysis and Goalkeeper Strategies  

![Penalty Analysis and Goalkeeper Strategies](/images/HK.png)  
 
- Identified and established key correlations between the direction of shot during a penalty and game specific factors like if player is facing home or away fans in front of the goal, team is leading or behind in goals, time in game and so on.#[Beyond the Kick](https://medium.com/@praneithranganath10/beyond-the-kick-a-data-driven-decomposition-of-penalties-b42bfc811b03)
- Derived strategies to save penalties by predicting the direction of shot using a KNN model developed on the insights above.

### Body Composition Scanner

![Body Composition Scanner Image](/images/project.png)  
- Used a pretrained Resnet model to extract silhouettes of front and left or right facing images of subjects.
- Extracted features from silhouettes such as area, solidity of contour.
- Established a linear relation between wrist size and neck circumference through a paper by Prof. John Verzani called "Human Proportions," which was later used for other component calculations like fat percentage, lean mass, and more.

### Classical Machine Learning Algorithms

- Implemented classical machine learning algorithms (Linear Regression, Logistic Regression, and SVM) from scratch using Python, NumPy, and SciPy, demonstrating strong foundational understanding of model optimization, regularization, gradient descent.
- Developed comprehensive evaluation metrics (Accuracy, RMSE, SSE, Precision, Recall) to assess model performance, improving the interpretability and robustness of predictions.

### F1 2021 – Visual Storyboard and Analytical Dashboard

![Formula1 Analysis Image](/images/Dashboard.png)  
- Crafted a data-driven story showcasing the season’s pivotal moments and dynamics, allowing audience to grasp complex factors such as race strategies, driver performance and points progression that contributed to the championship battle.#[Beyond the Finish Line](https://medium.com/@praneithranganath10/beyond-the-finish-line-exploring-the-numbers-and-stats-behind-the-epic-f1-2021-drivers-86389fcbb9f6)
- Designed an interactive dashboard on Tableau featuring key insights into driver performance and championship progression.

### Health Centre Database and Datawarehouse for Analysis

![Health Centre Database Image](/images/DW.png)  
- Designed a multidimensional model for tracking metrics with a focus on identifying diagnostic trends and regional hazards.
- Utilized AWS Glue jobs for ETL from PostgreSQL to Redshift, leveraging S3 buckets for intermediate storage and Lambda functions to automate job triggers for efficient data processing.


### European Football/Soccer Database Management System

![European Football Database Image](/images/DMA.png)  
- Architected and implemented a scalable and robust database system for the European football/soccer league using **MySQL** and **MongoDB**.
- Integrated **MySQL database** with **Python** using **SQLAlchemy** for data analysis.

### Timeseries Analysis of Human Activities

- Conducted timeseries analysis on human activity data, applying techniques such as **ARIMA**, **LSTM**, and **Prophet** models to forecast and understand patterns.

[Check out my GitHub for more projects and details!](https://github.com/P101010)
