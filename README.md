# Diabetes-Prediction
This project focuses on predicting the risk of diabetes using a dataset that includes various health metrics, such as glucose levels, blood pressure, insulin, BMI, and age. The goal is to build a logistic regression model to classify individuals at risk of diabetes and evaluate its performance through visualizations like ROC curves.


Introduction

Diabetes is increasingly threatening a large portion of the population, and no perfect cure exists for it yet. There are two primary types of diabetes: Type 1 and Type 2. Type 2 diabetes, also known as diabetes mellitus, is a chronic condition that impacts how the body processes blood sugar (glucose). This project focuses on diabetes mellitus.

Through extensive research, several parameters have been identified that contribute directly to the occurrence of diabetes mellitus. Using a dataset containing observations of individuals with and without diabetes, we aim to classify individuals who are at risk of developing diabetes.

Objectives

Investigate factors related to the risk of diabetes using a dataset of individuals with and without diabetes.

Build a logistic regression model to classify individuals at risk of diabetes.

Evaluate the model’s performance using visualizations, including ROC curves.

Identify areas for improvement, such as feature scaling and data cleaning, to enhance the model’s predictive power.

Dataset Description

The dataset, stored in CSV format as diabetes.csv, includes observations related to diabetes. Each row represents an individual, with the following variables:

Pregnancies: Number of times pregnant.

Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.

Blood Pressure: Diastolic blood pressure (mm Hg).

SkinThickness: Triceps skin fold thickness (mm).

Insulin: 2-hour serum insulin (µU/ml).

BMI: Body mass index (weight in kg/(height in m)^2).

DiabetesPedigreeFunction: Diabetes pedigree function.

Age: Age in years.

Outcome: Class variable indicating whether the individual has diabetes (1) or not (0).
