# Traffic Flow Prediction Using Machine Learning

## Project Overview

Traffic congestion is a major challenge in urban transportation systems, leading to increased travel time, fuel consumption, and environmental impact. This project develops a machine learning-based traffic flow prediction system capable of classifying traffic conditions into Low, Normal, Heavy, and High traffic categories using vehicle count data.

The objective is to compare the performance of multiple classification algorithms and identify the most effective model for traffic situation prediction.

---

## Problem Statement

Accurate traffic prediction enables transportation authorities to make informed decisions regarding traffic management and congestion control. Traditional monitoring approaches are often insufficient for handling large-scale traffic data, creating a need for intelligent data-driven prediction systems.

This project addresses this challenge by building and evaluating machine learning models using historical traffic data.

---

## Methodology

The project follows a complete machine learning pipeline:

* Data collection and preprocessing
* Missing value handling and feature selection
* Exploratory Data Analysis (EDA)
* Feature engineering and encoding
* Model training and evaluation
* Performance comparison

Three machine learning algorithms were implemented:

* Random Forest Classifier
* Support Vector Machine (SVM)
* Logistic Regression

---

## Dataset

The dataset contains traffic-related attributes including:

* Car Count
* Bike Count
* Bus Count
* Truck Count
* Total Vehicle Count
* Traffic Situation Labels

Source: Kaggle Traffic Prediction Dataset

https://www.kaggle.com/datasets/hasibullahaman/traffic-prediction-dataset

---

## Results

 Model                   Accuracy 

 Random Forest           99.66%   
 Support Vector Machine  89.92%   
 Logistic Regression     88.58%   

The Random Forest Classifier achieved the highest predictive performance and demonstrated superior classification capability across all traffic categories.

---

## Repository Structure

* `mini-project.ipynb` — Complete implementation notebook
* `Traffic.csv` — Primary dataset
* `TrafficTwoMonth.csv` — Additional dataset
* `ML_report(final).pdf` — Detailed project report

---

## Future Scope

* Real-time traffic prediction using live sensor data
* Integration with smart traffic management systems
* Deep learning-based traffic forecasting models
* Deployment as a web-based traffic monitoring application

---

## Author

Srushti Raju
B.Tech, Computer Science and Engineering
