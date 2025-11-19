# assignment06

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