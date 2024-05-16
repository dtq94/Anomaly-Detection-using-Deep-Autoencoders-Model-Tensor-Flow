# Deep Autoencoders for Anomaly Detection

This project focuses on building and deploying a deep learning model for anomaly detection using deep autoencoders. The model is designed to learn the distributions and relationships between features of normal transactions and identify anomalies.

## Objective
- Understand the theory behind autoencoders.
- Develop a deep learning model based on autoencoders to learn distributions and relationships between features of normal transactions.
- Deploy the model using Flask.

## Data Overview
The dataset used is a transaction dataset containing information on more than 100,000 transactions across several features.

## Tech Stack
- **Language:** Python
- **Packages:** Pandas, Numpy, matplotlib, Keras, TensorFlow
- **API Service:** Flask, Gunicorn

## Approach
1. **Understand Business Objective:** Grasp the goal of anomaly detection in transaction data.
2. **Understand the Data Using EDA:** Perform exploratory data analysis to comprehend the dataset.
3. **Normalize and Clean the Data Using Imputation:** Clean and preprocess the data for model training.
4. **Understand Idea Behind Autoencoders:** Learn the theory and concepts of autoencoders.
5. **Build a Base Autoencoder Model Using Keras:** Implement the initial autoencoder model.
6. **Tune the Model to Extract the Best Performance:** Optimize the model for better accuracy.
7. **Extract Predictions:** Use the model to predict anomalies in the dataset.
8. **Serve Model as API Endpoint Using Flask:** Deploy the model as a web service.

