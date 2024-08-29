# Machine Learning Classification Project

## Overview

This repository contains a machine learning classification project demonstrating the use of XGBoost and CatBoost classifiers, hyperparameter tuning with Bayesian optimization, and the implementation of scikit-learn pipelines. The project also includes data preprocessing steps such as one-hot encoding and handling null values with `SimpleImputer`.

## Project Components

### 1. **Data Preprocessing**
- **One-Hot Encoding**: Categorical features are transformed into binary vectors.
- **SimpleImputer**: Handles missing values by imputing them with the mean (for numerical features) or the most frequent value (for categorical features).

### 2. **Machine Learning Models**
- **XGBoost**: An efficient and scalable gradient boosting framework.
- **CatBoost**: A gradient boosting library that handles categorical features effectively.

### 3. **Hyperparameter Tuning**
- **Bayesian Optimization**: Used for optimizing hyperparameters to improve model performance.

### 4. **Pipeline Integration**
- **scikit-learn Pipelines**: Combines preprocessing and model training steps into a single pipeline to streamline workflows and ensure reproducibility.

## Installation

Clone this repository and install the required packages using pip:

```bash
cd Poisonous_Mushroomsv2.ipynb
pip install -r requirements.txt
