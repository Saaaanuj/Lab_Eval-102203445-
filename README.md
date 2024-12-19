# 🚗 Fuel Cell Performance Prediction using Regression Models

Welcome to the **Fuel Cell Performance Prediction** project! In this project, we aim to predict the performance of fuel cells using various regression models. We leverage the **PyCaret** library to streamline model comparison, evaluation, and optimization.

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Data Preprocessing](#data-preprocessing)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [How to Run the Code](#how-to-run-the-code)
- [License](#license)

## 🚀 Project Overview

This project uses the **Fuel Cell Performance Data** to predict a target variable (`Target1`). The dataset contains several features, and our goal is to use **pycaret** to predict the target variable. With the help of **PyCaret**, we are able to easily compare, train, and evaluate the models to find the best one for predicting fuel cell performance.

### 🔑 Key Steps

1. **Data Loading**: Importing the dataset containing features and target values.
2. **Data Preprocessing**: Cleaning the data by removing low-frequency classes and handling any imbalances.
3. **Modeling**: Comparing multiple regression models to identify the best-performing one.
4. **Evaluation**: Evaluating the selected model using the test dataset.
5. **Prediction**: Making predictions on unseen data.

---

## 💻 Dependencies

To run this project, you'll need to install the following Python libraries:

- **pandas**: For data manipulation and analysis.
- **pycaret**: For model comparison, training, and evaluation.
- **scikit-learn**: For machine learning tools, including train-test splitting.

### Installation

To install the required libraries, run the following command:

```bash
pip install pandas pycaret scikit-learn
