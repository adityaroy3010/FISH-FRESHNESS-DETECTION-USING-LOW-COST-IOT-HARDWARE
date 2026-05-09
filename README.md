# Intelligent System for Detecting Fish Freshness

This project uses **IoT hardware** and **machine learning models** to create a low-cost, real-time **fish spoilage detection system**. It is intended to identify spoiling in fish storage environments by looking for volatile organic compounds (VOCs) and deteriorating water quality.


## Problem Description
Because of microbial activity and enzymatic reactions, fish is one of the most perishable foods and spoils quickly. Conventional freshness testing techniques are labor-intensive, time-consuming, and need skilled workers. This project uses a **portable, non-invasive system** to solve the issue.

Hardware components include: **ESP32 Microcontroller**, **MQ135 Gas Sensor**, which detects ammonia and CO₂, and **TDS Sensor**, which monitors microbial byproducts in water.

## 🧠 Machine Learning Models Employed: Support Vector Machine (SVM), k-Nearest Neighbors (k-NN), and Decision Tree (DT)

To classify spoilage status as **Fresh**, **Moderately Spoiled**, or **Spoiled**, the models are deployed on the ESP32 after being trained on actual sensor data.

## 🖥️ Features: Real-time classification of spoilage
Model selection and comparison of performance
Predictions can be exported as CSV or PDF.
Visualization of feature importance based on SHAP
Access based on roles (Admin, End User, Data Scientist)
Cloud deployment using a Dockerized microservices architecture

## Evaluation Metrics: F1-Score, AUC-ROC, Accuracy, Precision, and Recall

## 🔧 Libraries & Tools
Python (TensorFlow, Scikit-learn)
- C++ (for ESP32 code embedded)
AWS EC2, Docker, and Plotly (for visual dashboards)
- SHAP (for interpretability of the model)


## 📌 Writers: Aditya Roy (RA2211003011539)
## 📌 Writers: Aparijit Chakraborty (RA2211003011539)
