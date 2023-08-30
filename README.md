# Machine Learning Project - Regression Analysis

## Overview

This repository contains the code and documentation for a machine learning project focused on regression analysis. The goal of this project was to predict the price of a house using supervised learning techniques. Initially, we trained a Linear Regressor model with a dataset, but it did not achieve the desired accuracy. As a result, we explored a more complex model, the Random Forest Regressor, which yielded improved results.

## Dataset

We began our project using a dataset for training a Linear Regressor model. However, due to the dataset's limitations and the complexity of the problem, the Linear Regressor's performance fell short of our expectations. 

Subsequently, we obtained a new dataset with a larger number of columns, which provided richer features for our machine learning models.

## Methods Implemented

To enhance the performance of our models and achieve better accuracy, we implemented various methods, including:

1. **Data Cleaning and Preprocessing**: We meticulously cleaned and preprocessed the data to ensure it was suitable for modeling.

2. **Hyperparameter Tuning**: We systematically searched for optimal hyperparameter values to improve the model's performance.

3. **Feature Selection**: We identified and removed the least relevant columns from the features, which helped reduce noise in the data.

4. **Bagging**: We applied bagging techniques to reduce variance by creating random subsets of the training dataset and training multiple decision trees based on them.

5. **Boosting**: We employed boosting to reduce bias in the model by iteratively adjusting the weight of the training data.

6. **Feature Importance Analysis**: We conducted feature importance analysis in Python to identify key predictors. The results were visualized using Tableau.

7. **Increasing Training Dataset Size**: We augmented the size of the training dataset to improve model robustness.

## Results

Through the diligent implementation of the above methods, we were able to significantly enhance the model's performance. Our initial Linear Regressor achieved an accuracy of approximately 70%. After incorporating these techniques, our Random Forest Regressor model achieved an accuracy of 76%, a notable improvement in predictive capability.

For more details and the implementation code, please refer to the project's Jupyter notebooks and scripts in the repository.
