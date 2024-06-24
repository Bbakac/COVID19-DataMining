# COVID19-DataMining

## Overview
This project aims to analyze and predict COVID-19 outcomes using various machine learning (ML) techniques. The project involves data preprocessing, visualization, and the evaluation of multiple ML models to uncover patterns and provide insights into factors affecting patient outcomes.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [How to Run](#how-to-run)

## Introduction
The COVID-19 pandemic has posed significant challenges globally. Leveraging machine learning techniques can provide valuable insights to better understand the disease, predict patient outcomes, and optimize treatment strategies. This project evaluates various ML models to predict COVID-19 outcomes based on patient data.

## Dataset
The dataset used in this project contains comprehensive information on COVID-19 patients, including demographics, comorbidities, hospitalization details, and mortality status. The data was sourced from a publicly available COVID-19 dataset.

### Features:
- Age
- Gender
- Date of Diagnosis
- Hospitalization Status
- ICU Admission
- Outcome (Alive/Dead)
- Obesity
- Medical Conditions (Hypertension, Diabetes, Heart Disease, etc.)
- COVID-19 Classification (Positive/Negative)

## Data Preprocessing
Data preprocessing is a critical step to ensure the quality and integrity of the dataset. The preprocessing steps include:
- Identifying and removing duplicate entries
- Converting placeholder values (97, 98, 99) to NaN
- Correcting invalid dates and categorical feature values
- Imputing missing values using statistical methods
- Balancing the dataset using SMOTE (Synthetic Minority Over-sampling Technique)

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was performed to visualize the relationships between variables and understand the data distribution. Various visualizations, including correlation heatmaps, pie charts, and bar charts, were used to illustrate key insights.

## Machine Learning Models
The following machine learning models were evaluated in this project:
- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes
- XGBoost
- Artificial Neural Network (ANN)
- k-Nearest Neighbor (kNN)

Each model was trained and optimized using the training data and evaluated on the test data.

## Evaluation Metrics
The performance of each model was assessed using standard metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## Results
The Artificial Neural Network (ANN) model achieved the highest performance with:
- Accuracy: 94%
- Precision: 94%
- Recall: 94%
- F1-Score: 94%

Other models, such as Decision Tree and Random Forest, also demonstrated strong results.

## Conclusion
This project provides valuable insights into the demographics and medical conditions influencing COVID-19 outcomes. The comprehensive analysis highlights the potential of machine learning techniques in managing the ongoing pandemic and aiding healthcare professionals in making informed decisions.

## Future Work
Future work can focus on:
- Incorporating additional features and domain-specific knowledge
- Employing advanced hyperparameter optimization techniques
- Investigating ensemble methods
- Extending analysis to include longitudinal data
- Continuously updating and retraining models with new data
- Implementing and testing models in real-world clinical settings
- Conducting cross-regional analysis

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/COVID19-DataMining.git

# Navigate to the project directory:
cd COVID19-DataMining

# Install the required dependencies:
pip install -r requirements.txt

# Run the Jupyter notebook:
jupyter notebook CovidDataMining_Project.ipynb
