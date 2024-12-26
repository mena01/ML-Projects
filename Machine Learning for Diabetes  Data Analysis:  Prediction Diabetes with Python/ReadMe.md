# Diabetes Classification using SVM

## Overview
This project demonstrates the use of Support Vector Machine (SVM) with a linear kernel to classify individuals as diabetic or non-diabetic based on a dataset with labeled columns. The goal is to build a machine learning model that achieves high accuracy in predicting diabetes status.

## Dataset
- **Rows**: 768
- **Columns**: 8 features + 1 label column
- **Label**: Binary classification:
  - `0`: Not a diabetic person
  - `1`: Diabetic person

## Features
The dataset includes 8 columns representing various features. The label column indicates the classification target.

### Feature Descriptions
1. **Pregnancies**: Number of times pregnant.
2. **Glucose**: Plasma glucose concentration.
3. **BloodPressure**: Diastolic blood pressure (mm Hg).
4. **SkinThickness**: Triceps skin fold thickness (mm).
5. **Insulin**: 2-Hour serum insulin (mu U/ml).
6. **BMI**: Body mass index (weight in kg/(height in m)^2).
7. **DiabetesPedigreeFunction**: Diabetes pedigree function.
8. **Age**: Age of the person (years).

## Model Details
- **Algorithm**: Support Vector Machine (SVM)
- **Kernel**: Linear
- **Libraries Used**:
  - NumPy
  - Pandas
  - Scikit-learn

