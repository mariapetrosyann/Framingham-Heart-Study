# Framingham Heart Study Prediction

This repository contains a machine learning project aimed at predicting patient outcomes and diagnosing cardiovascular diseases using healthcare data from the Framingham Heart Study. The project evaluates various machine learning models to determine the best approach for accurate predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Key Steps](#key-steps)
- [Models and Results](#models-and-results)
- [Feature Scaling](#feature-scaling)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to predict patient outcomes or diagnose diseases based on healthcare data. Specifically, this project focuses on predicting cardiovascular disease risk using the Framingham Heart Study dataset. Various machine learning models are compared to identify the most effective approach for this task.

## Data

The dataset used for this project is the Kaggle Framingham Heart Study dataset, available as `framingham.csv`. This dataset includes health and demographic features relevant to predicting cardiovascular disease.

## Key Steps

1. **Data Loading and Preprocessing:**
   - Load the dataset and handle any missing values or data imbalances.
   - Perform feature scaling using `StandardScaler` to normalize the data.

2. **Model Building:**
   - Train and evaluate different machine learning models, including:
     - **Logistic Regression**
     - **Neural Network**
     - **Decision Tree**
     - **Random Forest Classifier**

3. **Model Evaluation:**
   - Assess model performance using metrics such as accuracy and loss.

## Models and Results

### Logistic Regression

- **Accuracy:** [0.8597]

### Neural Network

The neural network model is defined as follows:

- **Architecture:**
  - **Dense Layer:** 256 units, ReLU activation
  - **Dense Layer:** 728 units, ReLU activation
  - **Dense Layer:** 256 units, ReLU activation
  - **Output Dense Layer:** 1 unit, Sigmoid activation

- **Performance:**
  - **Loss:** 0.5013
  - **Accuracy:** 0.8278

### Decision Tree

- **Accuracy:** 0.7535

### Random Forest Classifier

- **Accuracy:** 0.8526

## Contributing

Contributions are welcome! If you have suggestions for improvements or fixes, please open an issue or submit a pull request.
