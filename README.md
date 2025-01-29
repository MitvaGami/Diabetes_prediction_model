# Diabetes Prediction Model

This repository contains a machine learning model for predicting diabetes based on patient data. The model is built using Python and leverages the Support Vector Machine (SVM) algorithm for classification.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to predict whether a patient has diabetes based on various health metrics such as glucose levels, blood pressure, BMI, etc. The model is trained on the Pima Indians Diabetes Dataset, which is a widely used dataset for binary classification tasks.

## Dataset

The dataset used in this project is the **Pima Indians Diabetes Dataset**. It contains the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age in years
- **Outcome**: Class variable (0 or 1) indicating whether the patient has diabetes

The dataset is included in the repository as `diabetes prediction model.csv`.

## Installation

To run this project locally, you need to have Python installed along with the necessary libraries. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-model.git
   cd diabetes-prediction-model
2.Install the required Python packages:
pip install numpy pandas scikit-learn
## Usage
Ensure you have the dataset (diabetes prediction model.csv) in the same directory as the script.

Run the Python script to train and evaluate the model:
 python diabetesprediction.py
 
 The script will output the accuracy of the model on both the training and test datasets. It will also allow you to input custom data to make predictions.

## Model Evaluation
The model's performance is evaluated using accuracy scores:

Training Data Accuracy: The accuracy of the model on the training dataset.

Test Data Accuracy: The accuracy of the model on the test dataset.

The model achieves an accuracy of approximately 78% on the test dataset, which is a good baseline for further improvements.


## License
This project is licensed under the MIT License. See the LICENSE file for details.
