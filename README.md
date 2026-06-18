# Diabetes Prediction System

## Project Overview

This project uses Machine Learning to predict whether a person is diabetic or non-diabetic based on medical parameters such as glucose level, blood pressure, BMI, insulin level, and age. The model is developed using the Support Vector Machine (SVM) algorithm.

## Libraries Used

* Python
* NumPy
* Pandas
* Scikit-learn


## Dataset

The project uses the Diabetes Dataset containing medical information of patients and their diabetes status.

## Steps to train the model

### 1. Importing Required Libraries

The necessary Python libraries are imported for data manipulation, preprocessing, model training, and evaluation.

### 2. Data Collection

The diabetes dataset is loaded into google colab and read using pd.read_csv().

### 3. Data Understanding and Exploration

The dataset is examined to understand its structure, dimensions, data types, and statistical properties.

### 4. Data Preprocessing

The data set is organised and prepared for training.The values are scaled so that all the features can be used by machine learning model.

### 5. Feature and Target Selection

Input attributes are separated from the target variable. The medical parameters act as features, while the diabetes outcome acts as the target.

### 6. Data Splitting

The dataset is divided into training and testing sets for model development and evaluation.

### 7. Model Training

A Support Vector Machine (SVM) classifier is trained using the training dataset to learn patterns associated with diabetes.

### 8. Model Evaluation

The trained model is evaluated using accuracy metrics on both training and testing datasets.

### 9. Prediction

New patient data is provided to the model, and the system predicts whether the patient is diabetic or non-diabetic.

### 10. Result Generation

The final prediction result is displayed based on the patient's medical information.

## Conclusion

This project demonstrates the application of Machine Learning in healthcare. By analyzing patient health parameters, the system can predict diabetes and assist in early detection and decision-making.