# Overview
This repository contains a Multiple Disease Prediction System, an interactive web application built using Streamlit. The system employs machine learning models to predict the likelihood of three major diseases: Diabetes, Heart Disease, and Parkinson's Disease. It is designed for quick and user-friendly diagnosis based on patient data inputs.

# Features
## Diabetes Prediction: 
Predicts diabetes risk based on inputs like pregnancies, glucose levels, BMI, insulin, age, and more.
## Heart Disease Prediction: 
Analyzes parameters such as age, cholesterol levels, chest pain type, and blood pressure to assess heart disease risk.
## Parkinson’s Disease Prediction: 
Identifies Parkinson's disease using acoustic and clinical features like frequency metrics, jitter, shimmer, and other neurological parameters.

# Machine Learning Models
The system uses pre-trained models saved as .sav files:
Support Vector Machine (SVM) for Parkinson's prediction.
Logistic Regression for Diabetes and Heart Disease predictions.

# Tech Stack
Frontend: Developed using Streamlit to provide an intuitive and interactive user interface.
Backend: Machine learning models trained using scikit-learn and integrated with Streamlit.
File Handling: Models stored and loaded using Python’s pickle module.

# Input Parameters
Diabetes: Includes inputs like the number of pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, age, and diabetes pedigree function.
Heart Disease: Requires age, sex, chest pain type, cholesterol level, fasting blood sugar, and ECG results, among others.
Parkinson’s Disease: Needs frequency-related features (MDVP:Fo, MDVP:Fhi), jitter, shimmer, NHR, HNR, and more.
# Deployed_Link
https://maladieindicator-ffnkrc9qeftw9anfjyjykn.streamlit.app/
