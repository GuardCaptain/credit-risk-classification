# credit-risk-classification
Module20Challenge



In this module, we will be creating a logistic regression model to predict the risk of a loan defaulting. We will be using a dataset of historical lending activity from a peer-to-peer lending services company. Loan status of 0 will indicate a healthy loan, and 1 will indicate a loan that is at high-risk of defaulting.

For creating our logistic regression model, we start off by separating our X and y variables. The X variables are the features we will be looking at, and the y variable will be the loan status. After separating the variables, we create the training and test data by splitting the two using the scikitlearn function train_test_split. We then created our logistic regression model, fitted it to the training data, and then predicted it to the testing data.

From the logistic regression model, we were able to obtain high scores for the precision, recall, and accuracy. For the healthy loans (0), we were able to get almost perfect marks across the three, with a score of 1 in precision and accuracy, and a score of 0.99 for recall. However, for the high risk loans (1) we notice a drop in all three categories when compared to the healthy loan. The scores were 0.85 , 0.91, and 0.88 for precision, recall, and accuracy respectively.

With this, we can conclude that the logistic regression model performs quite well. And while the model predicts the healthy loans almost perfectly, we may be more interested in how well it performs at predicting the high-risk loans as that may be more important informatin for businesses. 