# Heart Disease Prediction

This is a machine learning classification project for predicting whether a patient has heart disease or not.

The project uses patient health data and follows a complete machine learning workflow from data exploration to model evaluation and saving the trained model.

## Project Goal

The goal is to predict heart disease based on medical features such as age, chest pain type, blood pressure, cholesterol, maximum heart rate, and exercise-related symptoms.

## What I Practiced

- Loading a real medical dataset
- Exploratory Data Analysis (EDA)
- Understanding target values
- Creating a binary target column
- Handling missing values
- Feature selection
- Encoding categorical features
- Train/test split
- Training a Random Forest classifier
- Evaluating model performance
- Saving the trained model

## Data Cleaning

Columns with very high missing values were removed:

- `id`
- `ca`
- `thal`

Missing values in numerical columns were filled using median values.  
Missing values in categorical columns were filled using the most frequent value.

## Model

Random Forest Classifier

## Result

The model achieved:

- Accuracy: 84.78%
- Precision for heart disease: 87%
- Recall for heart disease: 87%
- F1-score for heart disease: 87%

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- Google Colab

## Files

- `main.ipynb`
- `heart_disease_model.pkl`

## Notes

This project was built as part of my machine learning practice.  
It helped me understand medical classification, missing value handling, feature selection, and model evaluation.
