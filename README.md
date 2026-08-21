# Diabetes Prediction - Machine Learning Project

This repository contains our university project for the course Applied Machine Learning at Halmstad University.

## Project Description

The goal of this project is to predict whether a patient has diabetes based on medical measurements from the Pima Indians Diabetes Dataset.

This is a supervised machine learning classification problem. We developed and evaluated three different machine learning models:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

## Dataset

The project uses the Pima Indians Diabetes Dataset.

The dataset contains:

- 768 samples
- 8 input features
- 1 target variable: `Outcome`

The target variable indicates:

- `0` = No diabetes
- `1` = Diabetes

## Methodology

The following steps were performed:

1. Data exploration
2. Handling hidden missing values
3. Data preprocessing
4. Train-test split
5. Feature scaling using StandardScaler
6. Training and evaluation of three machine learning models

## Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## Results

Random Forest achieved the best overall performance among the three evaluated models.

## Files

- `Project.ipynb` - Contains the complete implementation and experiments.
- `Rapport.pdf` - Contains the complete project report, methodology, results, discussion, and conclusion.

## Course

Applied Machine Learning (7.5 credits)  
Halmstad University

## Project Members
- Salam Mohammad
- Hayat Aodi
- Marah Rouk
