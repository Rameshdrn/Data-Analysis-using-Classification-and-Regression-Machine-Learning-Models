# Data-Analysis-using-Classification-and-Regression-Machine-Learning-Models

**PROJECT1:**
**Machine Learning Classification and Regression Analysis**
**Classification Analysis**
This project focuses on classification analysis using various machine learning models and libraries. We evaluate the performance of these models and uncover potential reasons for poor test data performance.

**Reasons for Poor Test Data Performance:**

**Model Overfitting:**
Overfitting occurs when a model fits too closely to the training data, resulting in perfect accuracy for the training data but poor generalization to new data. Overfit models fail to perform well on classification or prediction tasks.
Unrepresentative Data Sample:
An unrepresentative sample does not reflect the distribution of characteristics in the target group, leading to biased results. Variances in model skill scores during cross-validation may indicate unrepresentative data.
To mitigate this issue, you can repeat the model evaluation process, such as cross-validation, to control for randomness in training the model.

**Regression Analysis**
This part of the project involves regression analysis using machine learning models and libraries. We examine the coefficients of a linear model and interpret their relationships in the context of the dataset.

**Understanding Coefficients:**

Coefficients in a linear model represent the impact of a feature on the target variable when other features are held constant.
It's crucial not to misinterpret coefficients as mere correlations but as the change in the outcome for each unit change in the associated feature, while other features are held constant.


**Project 2: Part 1 and Part 2**
In the second project, we conduct both classification and regression analyses. Part 1 involves classifying the SBA loans dataset using Random Forest and Logistic Regression models. In Part 2, we regress car prices based on machine learning models. We observe the impact of hyperparameter tuning and note the performance differences between XGB Regressor and Random Forest Regressor.

**Part 1: Classification of SBA Loans**

We employ Random Forest and Logistic Regression models for classification tasks on the SBA loans dataset and compare the scores with different methods.

**Part 2: Regression of Car Prices**

This section focuses on the regression of car prices using machine learning models.
Hyperparameter tuning is explored to enhance model performance.
Notably, XGB Regressor outperforms Random Forest Regressor for this specific dataset.


Please refer to the individual sections and notebooks for detailed insights and results related to each part of the project.
