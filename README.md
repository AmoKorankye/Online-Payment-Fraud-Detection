# Fraud Detection in Online Payment Transactions

This repository contains the code for the PayBox Project, which is designed to analyze and predict fraudulent transactions using machine learning techniques. The project is structured around a Jupyter notebook (`app.ipynb`) that guides the user through the data analysis and modeling process.

## Dataset

The dataset used in this project is a synthetic dataset created for the purpose of detecting fraudulent transactions. It is a binary classification problem where the goal is to predict whether a transaction is fraudulent or not. The dataset includes various features such as the type of transaction, the amount, the location, and the time of the transaction, among others.

The dataset can be downloaded from the following link: [Paysim1 Dataset on Kaggle](https://www.kaggle.com/ealaxi/paysim1/download).

## Code Overview

The `app.ipynb` notebook is the main entry point for this project. It is structured in a way that allows for a step-by-step exploration of the data and the development of the predictive model. The notebook is divided into several sections, each focusing on a different aspect of the data analysis and modeling process.

- **Data Loading and Exploration**: This section loads the dataset and provides an initial exploration of the data, including a summary of the features and a visualization of the distribution of the target variable.

- **Data Preprocessing**: Here, the raw data is cleaned and preprocessed to prepare it for the machine learning models. This may involve handling missing values, encoding categorical variables, and scaling numerical features.

- **Exploratory Data Analysis (EDA)**: This part of the notebook delves deeper into the data, looking for patterns and relationships that could be useful for the model. It includes visualizations and statistical analyses.

- **Feature Engineering**: In this section, new features are created from the existing ones to potentially improve the performance of the machine learning models.

- **Model Training and Evaluation**: The notebook then trains several machine learning models on the preprocessed data and evaluates their performance using appropriate metrics.

- **Model Selection and Optimization**: Based on the evaluation results, the best performing model is selected, and hyperparameter tuning is performed to further optimize its performance.

- **Prediction and Evaluation**: Finally, the optimized model is used to make predictions on a test set, and the results are evaluated to assess the model's ability to detect fraudulent transactions.

By following the steps outlined in the `app.ipynb` notebook, users can replicate the analysis and modeling process, and potentially adapt it to their own datasets or use cases.
