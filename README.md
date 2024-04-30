# Disease Predictor Web Application

This project is a disease predictor web application developed using the Streamlit framework and deployed on Streamlit Cloud. It utilizes a Logistic Regression machine learning algorithm to predict diseases based on user-input symptoms. Additionally, the application provides dietary recommendations, medications, and precautions for detected diseases.

# Overview

The Disease Predictor Web Application is designed to assist users in predicting potential diseases based on symptoms they provide. The application uses a trained Logistic Regression model, which achieves a remarkable 100% accuracy on the classification task.

# Methodology

The development of the Disease Predictor Web Application followed a structured data science project lifecycle, which typically includes the following phases:

1. Problem Definition
Identify the problem statement and objectives of the project. In this case, the goal is to build a web application that predicts diseases based on user-provided symptoms and offers relevant recommendations.

2. Data Collection
Gather relevant data sources that will be used to train and test the machine learning model. This may involve obtaining medical datasets containing symptoms, diseases, and related information.

3. Data Preprocessing
Clean and preprocess the collected data to prepare it for model training. This includes handling missing values, encoding categorical variables, and performing feature scaling.

4. Model Selection and Training
Choose an appropriate machine learning algorithm (in this case, Logistic Regression) for the classification task. Split the preprocessed data into training and testing sets, and train the model using the training data.

5. Model Evaluation
Evaluate the trained model's performance using appropriate metrics (e.g., accuracy, precision, recall). Fine-tune the model parameters if necessary to achieve optimal performance.

6. Web Application Development
Utilize the trained model to develop the disease predictor web application using the Streamlit framework. Design an intuitive user interface that allows users to input symptoms and view disease predictions and recommendations.

7. Deployment
Deploy the web application on a hosting platform such as Streamlit Cloud to make it accessible to users over the internet.

# Features
Symptom Input: Users can enter their symptoms through a user-friendly interface.

Disease Prediction: The application predicts potential diseases based on the symptoms entered.

Dietary Recommendations: Provides dietary advice tailored to the predicted disease.

Medication Suggestions: Offers medication recommendations related to the predicted disease.

Precautionary Measures: Suggests precautionary measures to manage or avoid the predicted disease.

# Technologies Used

Streamlit: Frontend framework used to build the web application.

Python: Programming language used for the backend development.

Logistic Regression: Machine learning algorithm employed for disease prediction.

Streamlit Cloud: Hosting platform used to deploy the web application.

# Usage
To use the Disease Predictor Web Application, follow these steps:

 Visit the Web App: Access the deployed web application using the provided URL.
 
Input Symptoms: Enter your symptoms into the designated fields.

Get Predictions: Click the "Predict" button to obtain disease predictions along with dietary recommendations, medication suggestions, and precautions.

# Model Details
Algorithm: Logistic Regression

Problem Type: Classification

Accuracy: 100%
