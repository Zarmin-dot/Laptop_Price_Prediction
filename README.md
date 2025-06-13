# Laptop_Price_Prediction

This repository contains a machine learning project focused on predicting laptop prices based on technical specifications. It demonstrates the complete workflow of a regression task using Python, including data preprocessing, feature engineering, model building, and performance evaluation.

Project Overview
Laptop prices vary significantly based on hardware attributes like processor, RAM, storage type, and screen resolution. The goal of this project is to train regression models that can accurately estimate laptop prices using these features.

Objectives
Understand how hardware features influence pricing

Clean and prepare raw data for modeling

Engineer useful features from semi-structured data

Train and compare multiple regression models

Evaluate model performance using error metrics and plots

Dataset
The dataset, sourced from Kaggle, contains laptop listings with attributes such as:

Company

TypeName

Inches

ScreenResolution

CPU

RAM

Memory

GPU

Operating System

Weight

Price (Target)

Methodology
Data Preprocessing
Removed duplicates and irrelevant columns

Standardized RAM (to GB) and Weight (to kg)

Parsed Memory into SSD and HDD components

Encoded categorical variables using label encoding

Feature Engineering
Extracted CPU and GPU brand/type

Converted screen resolution into pixel count

Selected meaningful features for modeling

Model Building
Implemented pipelines for preprocessing and modeling

Trained Linear Regression, Ridge Regression, and Random Forest models

Compared model performance using R² and RMSE on test data

Evaluation
Plotted predicted vs actual prices to visualize model fit

Inspected residuals for model diagnostics

Assessed overfitting by comparing train-test metrics

Tools and Libraries
Python

pandas, NumPy

scikit-learn

matplotlib

Results
The Ridge Regression and Random Forest models provided strong results, with reasonable R² scores and prediction accuracy. Feature importance was explored to understand model behavior.
