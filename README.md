## knn algorithm from scartch on iris data set

ALGORITHM:
* Step 1 − Load the training and test data.
* Step 2 − Choose the value of K i.e. the nearest data points. K can be any integer (preferably not 1, but any other odd value)
* Step 3 − For each point in the test data do the following −
* 3.1 − Calculate the distance between test data and each row of training data with Euclidean Distance Formula. 
* 3.2 − Based on the distance value, sort them in ascending order.
* 3.3 − Next, it will choose the top K rows from the sorted array.
* 3.4 – Compute the average of sum of the preceding rows and calculate the percentage error. The predicted value corresponds to the value with the least percentage error.
Step 4 − End
