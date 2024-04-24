# House-Price-Prediction

This repository contains code for a Kaggle competition focused on predicting house prices based on their characteristics. 

We first conducted an analysis of the variables and the information they provide to perform effective feature engineering. For the feature engineering process, new variables were created, a logarithmic function was applied to skewed distributions, missing values for categorical variables were filled using the mode or a constant value, and for numerical values, a KNN algorithm was applied to find nearby observations.

Next, we compared different models using PyCaret to identify the best-performing one. Finally, we utilized a hyperparameter optimization algorithm to fine-tune the model's parameters for optimal performance.
