# Kaggle House Prices Prediction - Top 9% Model

Overview

This repository contains my solution to the Kaggle House Prices: Advanced Regression Techniques data science competition, where I achieved a top 9% ranking among all submissions with a final RMSE of 0.1245. The competition challenged participants to predict housing prices based on various features of homes in Ames, Iowa.

Model Approach

The solution employs a stacked ensemble model combining Ridge, Lasso, and ElasticNet regressions. By optimizing hyperparameters and performing feature engineering, I built a robust model capable of accurately predicting housing prices. The final model is tuned using cross-validation to minimize overfitting and ensure generalization.

Key Techniques

	•	Feature Engineering: Handling missing data, scaling features, and applying log transformations to target variables.
	•	Regularization Models: Stacked ensemble of Ridge, Lasso, and ElasticNet models to handle multicollinearity and feature selection.
	•	Hyperparameter Tuning: Used GridSearchCV and ElasticNetCV to optimize regularization parameters for the best possible RMSE.

Achievements

	•	Top 9% in Kaggle competition (Ranked X out of Y participants)
	•	Final RMSE: 0.1245
