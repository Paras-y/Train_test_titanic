# Train_test_titanic

Titanic Dataset -
Train.csv will contain the details of a subset of the passengers on board (891 to be exact)
and importantly, will reveal whether they survived or not, also known as the “ground truth”.


The `test.csv` dataset contains similar information but does not disclose the “ground truth” for
each passenger. It’s your job to predict these outcomes.
Using the patterns you find in the train.csv data, predict whether the other 418 passengers
on board (found in test.csv) survived
	**Model-Score**

Random Forest	85.28

Gradient Boosting Classifier	84.77

Support Vector Machines	82.74

Logistic Regression	79.70

Decision Tree	79.70

Naive Bayes	78.68

Perceptron	78.68

Linear SVC	78.68

KNN	77.66

Stochastic Gradient Descent	75.13

**I have used the Random Forest model for the testing data as its accuracy came out to be the highest.**
