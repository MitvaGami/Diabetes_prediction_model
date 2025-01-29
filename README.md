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
