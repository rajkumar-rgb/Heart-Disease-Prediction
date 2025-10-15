# Heart Disease Prediction ❤️🫀

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3.2-orange?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Project Overview
This project implements a **Heart Disease Prediction system** using machine learning.  
It predicts whether a patient has heart disease based on medical features such as age, cholesterol, blood pressure, chest pain type, and more.  
The model is trained using a **Random Forest Classifier** to achieve accurate and reliable predictions.

---

## Dataset
- **File:** `heart.csv`  
- **Features:** Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Rest ECG Results, Max Heart Rate, Exercise-Induced Angina, ST Depression, Slope of ST, Number of Major Vessels, Thalassemia  
- **Target:** `condition` (converted to binary: 0 = No Disease, 1 = Disease)

---

## Project Workflow
1. **Data Loading & Cleaning** – Load the dataset and preprocess the target column.  
2. **Exploratory Data Analysis (EDA)** – Visualize distribution of data and feature correlations.  
3. **Feature Scaling** – Standardize features for better model performance.  
4. **Model Training** – Train a Random Forest Classifier.  
5. **Evaluation** – Measure accuracy, confusion matrix, and classification report.  
6. **Feature Importance** – Visualize top features contributing to predictions.  

---

## Results

### Accuracy
- ✅ **Test Accuracy:** ~[88]%  

### Confusion Matrix
![Confusion Matrix]
<img width="442" height="396" alt="image" src="https://github.com/user-attachments/assets/2bb9505a-34b7-437f-b538-70ad9e0cc267" />


### Feature Importance
![Feature Importance]
<img width="820" height="723" alt="image" src="https://github.com/user-attachments/assets/d08e4229-d8c4-48b8-84a1-06621177b750" />


---

## How to Run
1. Clone this repository:  
```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
