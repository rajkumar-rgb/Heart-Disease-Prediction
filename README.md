# Heart Disease Prediction

## Project Overview
This project implements a **Heart Disease Prediction system** using machine learning. It predicts whether a patient has heart disease based on key medical features such as age, cholesterol, blood pressure, chest pain type, and more. The model is trained using a **Random Forest Classifier** for reliable and accurate predictions.

## Dataset
- **File:** `heart.csv`
- **Features:** Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Rest ECG Results, Max Heart Rate, Exercise-Induced Angina, ST Depression, Slope of ST, Number of Major Vessels, Thalassemia
- **Target:** `condition` (converted to binary: 0 = No Disease, 1 = Disease)

## Project Workflow
1. **Data Loading & Cleaning**  
   Load the dataset and preprocess the target column for binary classification.
2. **Exploratory Data Analysis (EDA)**  
   Visualize data distribution and feature correlations using count plots and heatmaps.
3. **Feature Scaling**  
   Standardize features to improve model performance.
4. **Model Training**  
   Train a Random Forest Classifier on the training dataset.
5. **Evaluation**  
   Assess model performance using accuracy, confusion matrix, and classification report.
6. **Feature Importance**  
   Identify and visualize the top features contributing to predictions.

## Key Libraries
- `pandas` & `numpy` – Data handling and manipulation  
- `matplotlib` & `seaborn` – Data visualization  
- `scikit-learn` – Machine learning, preprocessing, and evaluation  

## Results
- ✅ **Model Accuracy:** ~[Insert your test accuracy]%  
- ✅ **Confusion Matrix:** Shows true vs predicted labels  
- ✅ **Classification Report:** Precision, Recall, F1-score for both classes  

## Visualizations
- Distribution of heart disease cases  
- Feature correlation heatmap  
- Confusion matrix heatmap  
- Top 10 important features influencing predictions  

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Heart-Disease-Prediction.git
