# EE4211-Taxi-Prediction
A project by three NUS students for EE4211 (Data Science for IoT), predicting taxi availability in Singapore using machine learning. The model analyzes real-time data (rainfall, UV index, carpark occupancy) to optimize urban mobility and fleet management, supporting Singapore’s Smart Nation initiative.

# Taxi Availability Prediction in Singapore
## Introduction
Urban transportation in Singapore faces unpredictable demand-supply mismatches, influenced by environmental and infrastructural conditions. This project aims to develop a machine learning-based forecasting model to predict taxi availability using real-time datasets, including rainfall, UV index, and carpark occupancy. By leveraging advanced predictive analytics, this project supports smart mobility planning and efficient fleet management for taxi operators and urban planners.

## Project Motivation
The increasing reliance on data-driven solutions for urban planning highlights the need for accurate taxi availability predictions. Heavy rainfall, high UV index levels, and parking availability significantly influence commuter behavior. This project integrates multiple data sources to create a reliable forecasting model, enabling:
- Commuters to access real-time taxi availability insights for better trip planning.
- Taxi Operators to optimize fleet distribution and reduce idle times.
- Urban Planners to identify patterns in transportation demand and enhance policy-making.
This project aligns with Singapore’s Smart Nation initiative, contributing to a more efficient, data-driven transportation system.

## Problem Statement
Singapore’s high population density and unpredictable weather often lead to mismatches in taxi demand and availability. Our goal is to:
- Develop a predictive model using environmental and transportation datasets to forecast taxi availability in real time.
- Analyze how different factors (rainfall, UV index, and carpark occupancy) impact taxi demand trends.
- Optimize fleet management strategies for taxi operators based on predictive insights.

## Proposed Solution
Our solution involves a multi-model machine learning approach, integrating data from multiple real-time sources to predict taxi availability. The system follows these steps:

1. Data Collection & Preprocessing
- Utilized API calls to data.gov.sg to extract real-time data on taxi availability, rainfall, UV index, and carpark occupancy.
- Performed data cleaning, feature engineering, and handling missing values to enhance dataset quality.

2. Machine Learning Models Implemented
- Ridge Regression – Used as a baseline model to capture linear relationships between features.
- Random Forest Regressor – An ensemble learning method that captures nonlinear dependencies in the dataset.
- Multi-Layer Perceptron (MLP) – A deep learning model trained to detect complex feature interactions and patterns in taxi availability.
- Hyperparameter tuning was conducted for each model to improve accuracy and generalization.

3. Evaluation & Performance Metrics
- Mean Squared Error (MSE) and R² Score to assess model accuracy.
- Pearson and Spearman correlation to analyze the relationships between environmental factors and taxi demand.
- A combined model approach outperformed individual datasets, achieving the lowest MSE and highest correlation scores.

## IoT System Vision
In a real-world deployment, our system could be integrated into a smart mobility application, where:
- Taxi operators receive predictive insights to adjust fleet distribution dynamically.
- Commuters access real-time forecasts via a mobile app to plan their trips more efficiently.
- Urban planners use historical demand patterns to develop future-proof transportation policies.
By providing actionable insights, this model supports Singapore’s efforts in reducing traffic congestion and enhancing public transport accessibility.

## Contributors
This project was developed by Group 23 as part of the EE4211 Data Science for IoT course at National University of Singapore (NUS).
1. Tan Kai Xin, Nicole
2. Peng Ziwei
3. Erik Naeslund
