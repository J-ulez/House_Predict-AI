# HousePredict AI 🏠📊

HousePredict AI is a machine learning-based backend system designed to predict UK housing prices using historical property data.  
The project combines software engineering principles with data science and machine learning techniques to build an accurate and scalable house price prediction engine.

---

## 📌 Project Overview

The UK housing market is influenced by several factors such as:

- Property location
- Number of bedrooms and bathrooms
- Property type
- Floor area
- Economic and regional factors

Traditional property valuation methods are often time-consuming and subjective.  
HousePredict AI automates this process by using machine learning algorithms to analyse housing datasets and generate reliable property price predictions.

This project was developed as part of a Software System Engineering coursework project.

---

## 🚀 Features

- Data preprocessing pipeline
- Missing value handling using `SimpleImputer`
- Feature encoding for categorical variables
- Feature scaling using `StandardScaler`
- Machine learning model training and evaluation
- House price prediction system
- Comparative analysis of models
- Modular backend-focused architecture

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Development Tools
- Google Colab
- Git & GitHub
- Trello
- Proto.io

---

## 🤖 Machine Learning Models

The project compares two regression models:

### 1. Linear Regression
Used as the baseline model for performance benchmarking.

### 2. Random Forest Regressor
Used to capture complex and non-linear relationships within housing data.

The Random Forest model produced more accurate predictions and handled outliers more effectively.

---

## ⚙️ Data Preprocessing Pipeline

The preprocessing stage includes:

- Handling missing values using `SimpleImputer`
- Encoding categorical features using `LabelEncoder`
- Normalizing features using `StandardScaler`
- Train-test splitting (80/20)

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Mean Squared Error (MSE)
- R-Squared Score (R²)

These metrics were used to measure prediction accuracy and model performance.

---

## 🏗️ System Architecture

The project follows a modular backend architecture consisting of:

1. Data Ingestion Layer
2. Preprocessing & Transformation Layer
3. Model Training Layer
4. Prediction & Evaluation Layer

This design improves scalability, maintainability, and future integration possibilities.

---
