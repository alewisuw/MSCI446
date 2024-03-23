# Used Car Value Prediction Project

## Overview

This project aims to predict the value of used cars using machine learning techniques. We utilized a dataset sourced from [Kaggle](https://www.kaggle.com/datasets/focusedmonk/true-value-cars-dataset/data), which contains various features of used cars along with their corresponding prices.

## Models Explored

We explored a total of eight different types of regression models, including:

- Adaboost
- Bayesian
- Elastic Net
- Lasso
- Linear
- Ridge
- Tree
- XG Boost

## Model Improvement

Among the models tested, AdaBoost initially showed the poorest performance. However, we improved its performance significantly through hyperparameter tuning. This involved adjusting key parameters to optimize the model's predictive accuracy.

## Boostrapping

Given that our dataset was small, we implemented bootstrapping as it allowed us to make the most out of the limited data we have by resampling from it with replacement

## How to Use

1. **Data**: Ensure you have access to the Kaggle dataset containing information on used cars.
2. **Environment Setup**: Set up your Python environment with necessary libraries such as Scikit-learn, XGBoost, etc.
3. **Code**: Run the provided Python scripts or notebooks to train and evaluate the machine learning models.
4. **Model Selection**: Compare the performance of the different models to select the one that best suits your needs.
5. **Hyperparameter Tuning**: Optionally, conduct hyperparameter tuning on the chosen model to further enhance its predictive capability.

## Dependencies

All the dependencies are in requirements.txt. Run the command below.

`pip install -r requirements.txt`

## Contributors

- Victor Su, Arkhan Lewis, Chintan Desai, Parth Desai, Chris Qu
