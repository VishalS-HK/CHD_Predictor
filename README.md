# Coronary Heart Disease Risk Prediction

This project aims to predict the 10-year risk of coronary heart disease (CHD) based on demographic, behavioral, and medical data. Two models, Logistic Regression and Neural Network, were used for the prediction task.

## Dataset

The dataset used for this project contains the following features:

- **Demographic data:**
  - Male: Binary variable indicating gender (1 for male, 0 for female).
  - Age: Age of the patients.

- **Behavioral data:**
  - Current smoker: Binary variable indicating whether the patient is a smoker.
  - Cigs per day: Average number of cigarettes smoked per day.
  - BP meds: Binary variable indicating whether the patient is on blood pressure medications.
  - Prevalent stroke: Binary variable indicating whether the patient had previously had a stroke.
  - Prevalent Hyp: Binary variable indicating whether the patient is hypertensive.
  - Diabetes: Binary variable indicating whether the patient has diabetes.

- **Medical data:**
  - Tot Chol: Total cholesterol level.
  - Sys BP: Systolic blood pressure.
  - Dia BP: Diastolic blood pressure.
  - BMI: Body Mass Index.
  - Heart Rate: Heart rate.
  - Glucose: Glucose level.

- **Target variable:**
  - 10-year risk of coronary heart disease (CHD).

The dataset can be found on Kaggle or in this Repository.</br>
[Kaggle](https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression?resource=download)

## Models Used

Two models were employed for predicting the 10-year risk of CHD:

1. **Logistic Regression:** Logistic Regression is a widely used statistical model for binary classification. It models the relationship between the independent variables and the probability of an event occurring. In this project, Logistic Regression was used to predict the risk of CHD based on the provided features.

2. **Neural Network:** A Neural Network is a powerful machine learning model that can capture complex relationships between variables. It consists of multiple layers of interconnected nodes (neurons) that learn to recognize patterns in the data. In this project, a Neural Network was trained to predict the risk of CHD using the input features.


You can find my Jupyter Notebook containing the code for this project [here](https://github.com/VishalS-HK/CHD_Predictor/blob/main/main3.ipynb).
