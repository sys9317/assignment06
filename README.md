# assignment06
This my work for assignment 06 which covers classification, metrics,
and concepts of maching learning.

From exercise 1 to 3, I have used knitr::include_graphics() function to show
how I calculated MSE, RMSE, MAE, confusion matrix, accuracy, precision and 
recall, and misclassification rate by hand. 

For exercise 4, I wrote my thought process on why is it 
important to consider context of dataset itself when comparing
calculated accuracy in different supervised maching learning tasks
since it is easy to fall to accuracy paradox where
higher accuracy does not mean that better predicion since your dataset
could be highly imbalanced. 

For exercise 5, I set me seed to 20200229 so that I can replicate and generate
same answers. Then, I used initial split to split my dataset into training and 
testing dataset where training dataset has 80% of observations. 

After that, I used count() to see how many different types of marbles are in 
the testing dataset, and used ggplot (including geom_title) to visualize my 
testing dataset. 

In part 3, I have generated a function that takes a vector of sizes and
returns a vector of predicted color, and then apply it to the testing data using
"$. In part 4, I made function called "calculation" which calculates accuracy
and generate confusion matrix using color and color_predicion column from 
testing dataset. 

In part 5, I have generated a decision tree that predicts frequencies of marbles
using the training dataset. 

