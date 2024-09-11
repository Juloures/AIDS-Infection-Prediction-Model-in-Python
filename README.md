# AIDS Infection Prediction Model

This repository contains a machine learning project aimed at predicting HIV infection status using patient health data. The project utilizes various classification algorithms to analyze different features related to patients' medical histories and provides a binary classification: infected or not infected.

## Problem Description

We are working on a binary classification problem, predicting whether a patient is infected by HIV (AIDS) based on several medical and personal attributes, such as age, weight, CD4/CD8 cell counts, and more. The dataset includes multiple risk factors, including intravenous drug use, sexual behavior, and previous treatment histories.

## Dataset

The project uses four different CSV files:
- `AIDS_Classification.csv`
- `AIDS_Classification_5000.csv`
- `AIDS_Classification_15000.csv`
- `AIDS_Classification_50000.csv`

Each file contains patient information with various numbers of records, enabling performance evaluation across different dataset sizes.

## Features

The dataset contains attributes such as:
- Age
- Weight
- Medical history (e.g., hemophilia, intravenous drug use)
- CD4/CD8 cell counts
- Karnofsky score
- Race and gender
- History of antiretroviral therapy

## Models

Various machine learning models are used to perform the binary classification:
- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)
- XGBoost

The model's performance is evaluated using the following metrics:
- Accuracy
- Precision
- Recall (Sensitivity)
- Specificity
- F1-score

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/username/aids-infection-prediction.git
