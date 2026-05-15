# Heart-Disease-UCI
# Heart Disease Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Heart Disease dataset using Python libraries such as Pandas, Matplotlib, and Seaborn.

The objective of this project is to analyze patient health data, understand feature relationships, visualize patterns, and prepare the dataset for machine learning models that can predict heart disease.

The project helps in understanding how different medical attributes may affect heart disease risk.

---

# Dataset Information
The dataset contains medical information collected from patients.

## Features in Dataset

| Column Name | Description |
|---|---|
| age | Age of the patient |
| sex | Gender of the patient |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Cholesterol level |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels |
| thal | Thalassemia type |
| target | Presence of heart disease |

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
   Google Colab
  sklearn
  linear regression

---

---

# Machine Learning Steps Performed

The following machine learning workflow was completed after Exploratory Data Analysis (EDA):

## 1. Data Preprocessing
- Loaded and inspected the dataset
- Checked missing values
- Verified data types
- Explored feature distributions

## 2. Feature and Target Separation
- Independent features were separated into X
- Target column was separated into Y

## 3. Train-Test Split
- Dataset was divided into:
  - Training data
  - Testing data
- This helps evaluate model performance on unseen data

## 4. Model Selection
A classification algorithm was selected for prediction of heart disease.

Example models that can be used:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## 5. Model Training
- The selected model was trained using training data
- The model learned patterns from dataset features

## 6. Model Prediction
- Predictions were generated using testing data
- Predicted values were compared with actual values

## 7. Model Evaluation
The model performance was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1 Score

## 8. Performance Analysis
- Model accuracy was analyzed
- Prediction capability was evaluated
- Feature importance and relationships were observed

## 9. Future Improvements
Possible improvements for better performance:
- Feature Scaling
- Feature Selection
- Hyperparameter Tuning
- Cross Validation
- Trying multiple algorithms
- Improving dataset quality

---
