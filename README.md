# Data-Science-Experiments
XGBoost(Xtreme Gradient Boosting)is a very powerful tool for classification and regression. It is an implementation of the Gradient Boosted Decision Trees algorithm. In Gradient Boosted Decision Trees algorithm we go through cycles that repeatedly build new models and combine them into an ensemble model. For making a prediction, we can add the predictions from all previous models and use these predictions to calculate new errors, build the next model, and add it to the ensemble.
For reading data environment is set up using library. The core xgboost function requires data to be a matrix. It has a built-in data type, DMatrix, that is particularly good at storing and accessing sparse matrices efficiently. After loading the data it is shuffled to divide it into training and testing data set.
For training a model the following are required:
•	What training data to use
•	The number of training rounds
•	What the objective function is
Over-fitting: When model relies too much on randomness/noise in the training set to make its classifications, it will probably not extend well to a new dataset.
Ways to improve model performance
•	Account for the fact of imbalanced classes
•	Train for more rounds
Final step is interpreting the model created. Xgboost has a lot of built-in functions to help figure out why model is making the distinctions in its making. One way that we can examine our model is by looking at a representation of the combination of all the decision trees in our model.
