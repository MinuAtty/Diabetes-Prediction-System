# 🩺 Diabetes Prediction System

## Table of Contents
- [Overview](#overview)
- [Features](#🔍features)
- [Technologies Used](#🧪technologies-used)
- [Machine Learning Model](#🧠machine-learning-model)
- [Recommendation System](#📈recommendation-system)

## Overview
A Django-based web application that predicts the likelihood of diabetes in individuals using machine learning. The system provides tailored lifestyle recommendations, preventive tips, and diabetes management advice based on user inputs such as age, gender, BMI, and physical activity level.

## 🔍 Features

✅ Diabetes Risk Prediction using a trained ML model

📊 BMI Calculation from height and weight inputs

🍎 Lifestyle & Food Recommendations based on results

📷 Upload options for sugar reports and meal images

📁 Personalized dashboard with result history

💬 Clear explanation of prediction reasons

🔐 User-friendly interface built with Django


## 🧪 Technologies Used
- Python (scikit-learn, pandas, matplotlib)
- Django (web framework)
- HTML/CSS/Bootstrap (frontend)
- SQLite (default DB)
- Joblib/Pickle (for model serialization)

## 🧠 Machine Learning Model
- Algorithm: Logistic Regression / Random Forest (select based on performance)
- Input Features: Gender, Age, Height, Weight, Exercise/Sports Activity
- Output: Diabetes Positive / Negative
- Evaluation Metrics: Accuracy, Precision, Recall, Confusion Matrix

## 📈 Recommendation System
Depending on the result:
- If Positive: Offers lifestyle modifications, food suggestions, doctor visits.
- If Negative: Preventive measures, activity suggestions, healthy diet tips.

