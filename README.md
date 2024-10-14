# Boston-dmv
Train predictive models using logistic regression and decision trees and evaluate the performance of those models. You have to decide which model you choose.

The dataset coming from the library(MASS)

data(Boston)


Originally, this dataset is for Regression tasks. However, you should perform classification for the assignment by following this condition.

Transform the label(target variable) which is 'medv' into 2 class  where

medv <= 21 --> low

medv >21 --> high
