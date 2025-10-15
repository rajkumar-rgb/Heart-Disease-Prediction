# Heart Disease Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24-orange?logo=scikitlearn) ![Pandas](https://img.shields.io/badge/Pandas-1.5-green?logo=pandas) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-red?logo=matplotlib)

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Author](#author)

## Project Overview
Heart disease is one of the leading causes of death worldwide. Early prediction can save lives by alerting patients and doctors in time.  
This project uses machine learning models to predict the likelihood of heart disease based on various medical attributes.

## Dataset
The project uses the [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-uci) from Kaggle.  
It contains **303 records** and **14 features** related to patient health indicators.

## Features
| Feature | Description |
|---------|-------------|
| age | Age of the patient |
| sex | Gender (1 = male, 0 = female) |
| cp | Chest pain type (4 values) |
| trestbps | Resting blood pressure (in mm Hg) |
| chol | Serum cholesterol in mg/dl |
| fbs | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| restecg | Resting electrocardiographic results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina (1 = yes; 0 = no) |
| oldpeak | ST depression induced by exercise relative to rest |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect) |
| target | Diagnosis of heart disease (1 = yes; 0 = no) |

## Model
This project explores multiple machine learning algorithms including:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting Classifier

The **best-performing model** is used for final predictions.  

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
