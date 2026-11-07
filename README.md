# SWYNEX Internship — Task 3: Modeling and Evaluation

## 📌 Project Overview

This project is completed as part of the **SWYNEX Internship — Task 3: Modeling and Evaluation**.

The objective of this task is to build, train, and evaluate a simple machine learning model for predicting students' final scores based on selected academic performance features.

## 🎯 Objective

The main objectives of this project are:

- Prepare the dataset for machine learning.
- Select relevant features for prediction.
- Build a baseline regression model.
- Train the model using training data.
- Predict student final scores.
- Evaluate the model using suitable regression metrics.
- Analyze the model's performance and limitations.

## 📊 Dataset

The dataset contains student academic and demographic information.

The main features used for modeling are:

| Feature | Description |
|---|---|
| `attendance_pct` | Student attendance percentage |
| `study_hours_per_week` | Average study hours per week |
| `previous_score` | Student's previous academic score |

### Target Variable

`final_score` — The student's final academic score.

## 🤖 Machine Learning Model

A **Linear Regression** model was used as the baseline regression model.

Linear Regression was selected because it provides a simple and interpretable baseline for predicting a continuous target variable such as final score.

## 📏 Evaluation Metrics

The model was evaluated using the following metrics:

- **MAE (Mean Absolute Error)** — Measures the average absolute difference between actual and predicted values.
- **MSE (Mean Squared Error)** — Measures the average squared prediction error.
- **RMSE (Root Mean Squared Error)** — Represents the prediction error in the same unit as the target variable.
- **R² Score** — Measures how well the model explains the variation in the target variable.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Inspection
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Predictions
   ↓
Model Evaluation
   ↓
Performance Analysis
```

## 📈 Results

The model performance is evaluated using MAE, MSE, RMSE, and R² Score.

The notebook also includes an **Actual vs Predicted Final Scores** visualization to compare the model's predictions with the actual values.

## ⚠️ Limitations

- The dataset contains a relatively small number of observations.
- Linear Regression assumes a linear relationship between the selected features and final score.
- Only a limited number of features were used.
- The model may not generalize well to students outside the characteristics represented in the dataset.
- More data and additional relevant features could improve prediction performance.

## 🚀 Future Improvements

Possible improvements include:

- Collecting a larger dataset.
- Adding more relevant academic and behavioral features.
- Testing other regression algorithms.
- Using cross-validation.
- Performing hyperparameter tuning.
- Comparing multiple models to identify the best-performing approach.

## 📁 Repository Contents

```text
SWYNEX-Modeling-and-Evaluation/
│
├── README.md
├── SWYNEX_Modeling_and_Evaluation.ipynb
└── cleaned_student_data.csv
```

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

## 👨‍💻 Internship

**SWYNEX Technologies — Python/Data Science Internship**

**Task 3: Modeling and Evaluation**

This project demonstrates the application of a basic machine learning regression workflow, from feature selection and model training to evaluation and interpretation.
