## assignment06

This assignment walks through a series of exercises focused on error measurement, 
data exploration, prediction, and model building in R. After loading tidyverse 
and dplyr, Exercise 01 visualizes provided error-calculation work and computes 
the error, squared error, absolute error, MSE, RMSE, and MAE for a set of true 
and predicted values. Exercises 02 and 03 include additional reference graphics.
Exercise 04 explains how class imbalance affects accuracy and why accuracy alone
can be misleading. Exercise 05 loads a marbles dataset, creates an 80/20 
 training–testing split, and visualizes the distribution of marble colors 
 and sizes using a heatmap. A simple rule-based prediction function is 
 created to guess color from size, and its performance is evaluated 
 through accuracy and a confusion matrix. The exercise then builds a 
 CART decision tree model using tidymodels and rpart, visualizes the 
 resulting tree, and compares how the model’s predictions differ from 
 the earlier manual rule due to the data-driven structure learned 
 from the training set.
 Lastly, the decision tree shows how the R software makes prediction.

## Assignment 07
 This repository contains the full workflow for two applied machine-learning 
 exercises completed using the tidymodels framework in R including 
 model training, cross-validation, evalation, and prediction.
 Exercise 1 uses restaurante inspection data and exercise 2 uses Chicago
 ridership data to build and evaluate several regression models, ultimately 
 producing predictions for 20 new observations.
 Both exercises demonstrate the full supervised learning workflow, including 
 data cleaning, feature engineering, cross-validation, model comparison, 
 and out-of-sample evaluation.
 The  restaurant dataset is converted into a binary classification issue 
 ("A" vs. "Not A") in Exercise 1.To improve prediction power, different factors  
 are designed.  A training/testing split is used to fit and assess a decision tree model.  
 To evaluate classification performance, confusion matrices, precision, 
 and recall are calculated. 
 The results show that the model is straightforward and easy to understand, 
 but it somewhat underfits the data.  Richer feature engineering and more 
 adaptable algorithms (random forests, boosted trees) are potential enhancements.

 Exercise 2 focus on predicting Chicago ridership data using different regressions
 including hyperparameteres as well. After preparing date-based predictors (weekday, month, yearday), 
 the modeling set is split into training and testing data and used to build a 
 preprocessing recipe with holiday indicators. Ten-fold cross-validation is used 
 to train and compare three regression models: a tailored random forest, KNN, and linear regression.  
 The random forest has the lowest average RMSE when RMSE is calculated across all folds and plotted for every model.  
 Last_fit() is used to estimate an out-of-sample RMSE on the testing set using 
 the finished random forest. Lastly, ridership forecasts are produced for the 
 20-row implementation dataset. 