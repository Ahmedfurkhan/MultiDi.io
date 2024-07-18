# MultiDi: AI-Driven Disease Prevention and Management Platform (AIDPM)

The MultiDi: AI-Driven Disease Prevention and Management Platform (AIDPM) is a cutting-edge solution designed to leverage advanced Data Science, Machine Learning (ML), and Artificial Intelligence (AI) techniques to predict, prevent, and manage a wide range of diseases.

## Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Running the Streamlit App](#running-the-streamlit-app)
4. [Jupyter Notebooks](#jupyter-notebooks)
5. [Implementation Details](#implementation-details)
6. [License](#license)

## Overview

MultiDi aims to address significant health challenges by providing an AI-powered solution that offers predictive analytics, personalized recommendations, and continuous health monitoring to effectively prevent and manage diseases such as diabetes, heart disease, and Parkinson's disease.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ahmedfurkhan/multidi.git
   cd multidi
2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Additional libraries for Jupyter Notebooks:**
   You may need to install additional libraries to run the Jupyter notebooks provided. Use the following command to install common dependencies:
   ```bash
   pip install jupyter pandas numpy scikit-learn matplotlib xgboost

## Running the Streamlit App

**1.Run the Streamlit app:**
    ```bash
    streamlit run app.py
    Open your web browser:
    Open your web browser and navigate to http://localhost:8501 to access the MultiDi platform.

**2.Jupyter Notebooks**
The project includes several Jupyter notebooks that demonstrate the implementation of predictive models for various diseases. These notebooks provide insights into data preprocessing, exploratory data analysis (EDA), machine learning modeling, and model evaluation.

1.Diabetes Prediction: Multiple disease prediction system - diabetes.ipynb
2.Heart Disease Prediction: Multiple disease prediction system - heart.ipynb
3.Parkinson's Disease Prediction: Multiple disease prediction system - Parkinsons.ipynb
To run the notebooks, navigate to the project directory and start Jupyter Notebook:
bash
jupyter notebook
Then open the respective notebook files to explore the implementation details.

## Implementation Details
### Basic Visualizations on Real-World or Augmented Data
**Diabetes Prediction:**
1.Histogram: Display the distribution of glucose levels.
2.Box Plot: Show the distribution of age.
3.Scatter Plot: Illustrate the relationship between BMI and glucose levels.
**Heart Disease Prediction:**
1.Histogram: Display the distribution of cholesterol levels.
2.Box Plot: Show the distribution of resting blood pressure.
3.Scatter Plot: Illustrate the relationship between maximum heart rate and age.
**Parkinson's Disease Prediction:**
1.Histogram: Display the distribution of MDVP(Hz).
2.Box Plot: Show the distribution of spread1.
3.Scatter Plot: Illustrate the relationship between PPE and RPDE.
### Simple Exploratory Data Analysis (EDA)
**Diabetes Prediction:**
1.Descriptive statistics for features like age, BMI, glucose, and insulin levels.
2.Correlation matrix to identify relationships between features.
**Heart Disease Prediction:**
1.Descriptive statistics for features like age, cholesterol, resting blood pressure, and maximum heart rate.
2.Correlation matrix to identify relationships between features.
**Parkinson's Disease Prediction:**
1.Descriptive statistics for features like MDVP \n
(Hz), MDVP\n
(%), spread1, and PPE.
2.Correlation matrix to identify relationships between features.
### Machine Learning Modeling
**Diabetes Prediction:**
1.Model: Support Vector Machine (SVM).
2.Evaluate using metrics such as accuracy, precision, recall, and F1-score.
3.Save and load the trained model for future predictions.
**Heart Disease Prediction:**
1.Model: Logistic Regression.
2.Evaluate using metrics such as accuracy, precision, recall, and F1-score.
3.Save and load the trained model for future predictions.
**Parkinson's Disease Prediction:**
1.Model: XGBoost.
2.Evaluate using metrics such as accuracy, precision, recall, and F1-score.
3.Save and load the trained model for future predictions.
# Live Demo 
##### [MultiDi.io](https://multidi.streamlit.app/)
##### [MultiDiFeyyn.com](https://www.youtube.com/watch?v=B9synWjqBn8&list=RDwagn8Wrmzuc&index=14)

