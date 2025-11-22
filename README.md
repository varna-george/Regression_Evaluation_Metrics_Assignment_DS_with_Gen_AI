Regression Evaluation Metrics Assignment

Objective:
The objective of this assignment is to evaluate the understanding of regression techniques in supervised learning by applying them to a real-world dataset and analyzing their performance through comprehensive evaluation metrics.
Dataset:
California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices.

Key Components Fulfilled:
1. Dataset Loaded and Preprocessed
2. Regression Algorithms Implementated: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, Support Vector Regressor (SVR)
3. Evaluated the performance of each algorithm using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared Score (R2)
   
Best-performing algorithm: Random Forest Regressor
Worst-performing algorithm: Linear Regression

5. Cross-Validated and Hyperparameter Tuned
Performed k-fold cross-validation (k=5) for all models to ensure robust performance evaluation.
Used GridSearchCV to fine-tune the hyperparameters of each model.
After tuning:
Best regression model: Gradient Boosting Regressor
