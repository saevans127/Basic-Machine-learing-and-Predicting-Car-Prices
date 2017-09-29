# Basic-Machine-learing-and-Predicting-Car-Prices
Using KNeighborsRegressor to predict car prices and to find error metrics (root mean squared errors) for different training and testing methods.
K-Nearest Neighbors uses Euclidean distance to find the most simialr cases in the train dataset in order to make predictions on the test dataset. It uses k number of neighbors to do this.
We specify what columns (test columns) we want to use to determine similarity to predict the target column, in this case price.
In this project we only use numerical characteristics for predctions. 
Our error metric will be the Root Mean Squared Error (RSME) to determine how accurate our predictions were. The lower the RSME, the better the predictions. We will use different k values, and different characteristics to find the different RSME
We will also use different number of folds to train and test data. A fold is the k number of times the dataset is partitioned ad each partition is used as a train and test set. 
