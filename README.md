# Coursera_Project__Loan_Default_Prediction

The goal of this project was to develop an ML model that can predict whether someone will default on their loan at the time of application. The first iteration of the model was submitted and assessed based on its final ROC-AUC score, reaching an accuracy score of 73 in the 63rd percentile.

Data cleaning, encoding, correlation analysis, variance thresholding, and RFECV (Recursive Feature Elimination with Cross-Validation) were utilized. Due to the nature of the predictor variable (Default) being a binary "Yes" or "No," logistic regression was used as the model for the first iteration.

The plan is to incorporate feature engineering to determine which features can be combined and/or refactored to improve prediction strength. Additionally, hyperparameter tuning will be implemented after RFECV to enhance the selection of significant features further.