# ✈️ Flight Delay Prediction using Machine Learning

This project demonstrates an end-to-end machine learning workflow to predict whether a flight will experience a **significant delay (≥ 60 minutes)** using historical flight data.

The main purpose of this project is **learning and skill development**, focusing on applying machine learning concepts to a real-world dataset and understanding the full process from raw data to model evaluation.

---

## 🎯 What We Learned from This Project

Through this project, we gained practical experience with the complete machine learning lifecycle.

### 📊 Data Handling & Preparation
- Importing and exploring real-world datasets using Pandas
- Selecting relevant columns and removing unnecessary features
- Checking and handling missing values
- Converting date columns into usable datetime formats
- Understanding how data quality affects model outcomes

### 🧠 Feature Engineering
- Creating time-based features such as **month** and **day of week**
- Encoding categorical variables using **one-hot encoding**
- Defining a binary target variable based on flight delay duration
- Learning how feature choices impact model performance

### 🔍 Exploratory Data Analysis (EDA)
- Analyzing flight delays by airline, day of week, and origin airport
- Visualizing data distributions to identify trends and patterns
- Interpreting EDA results to better understand the problem domain

### 🤖 Machine Learning Modeling
- Splitting data into training and testing sets
- Training a baseline **XGBoost classifier**
- Understanding how gradient boosting works for classification problems
- Applying machine learning to a real operational use case

### 📈 Model Evaluation & Interpretation
- Evaluating model performance using:
  - Accuracy
  - Confusion Matrix
  - ROC Curve
  - AUC Score
- Learning why accuracy alone can be misleading with imbalanced data
- Interpreting model results in a real-world context

### 🚧 Limitations & Improvements
- Recognizing class imbalance in delay prediction
- Understanding potential data leakage issues
- Learning the importance of cross-validation and hyperparameter tuning
- Seeing that machine learning models require iteration and refinement

---





## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Jupyter Notebook

---

## 📊 Model Summary

- **Problem Type:** Binary classification  
- **Target Variable:** Flight delayed ≥ 60 minutes (Yes / No)  
- **Model Used:** XGBoost Classifier (baseline)  
- **Evaluation Metrics:** Accuracy, ROC AUC, Confusion Matrix  

> This model is built for educational purposes and should not be used for real-world airline decision-making.

---

## 🚀 Future Enhancements

- Hyperparameter tuning to improve performance
- Cross-validation for more robust evaluation
- Addressing class imbalance using techniques like SMOTE or class weighting
- Adding weather and seasonal features
- Deploying the model as a web or cloud-based API

---

## 🔓 Code Usage

This project is **open for anyone to use, learn from, and modify**.

You are free to:
- Use this code for learning or academic purposes
- Adapt the workflow for other datasets
- Extend the project with additional features or models



## 👤 Author

Rojina Dhakal 
Academic Machine Learning Project  
