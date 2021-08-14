# Code for MinorProject-1

## Dataset Link: https://s3.us-west-2.amazonaws.com/public.gamelab.fun/dataset/salary_d


## Reference: https://towardsdatascience.com/machine-learning-simple-linear-regression-with-python-f04ecfdadc13


### Theory Questions

**Question 1: What is overfitting and how to avoid it?**

***Answer:*** It is a condition where the model fits and performs very well in Training Data but when it comes to Unseen Data(Testing) it doesn't performs well. It would be a highly biased prediction and we will not be able to get the desired results.

We can avoid overfitting by tuning the hyperparameters, reducing the learning rate, changing the ratio of train and test data set, tuning the model to a generalised prediction, improving the quality of the dataset by cleaning the dataset and much more ways can helps in reducing Overfitting.

**Question 2: What is RMSE and MSE? How can you calculate them?**

***Answer:*** 

*RMSE:* Root Mean Square Error

*MSE:* Mean Squared Error

They are loss or cost functions whcih are used to estimate the correctness or working of a model. RMSE takes the root of the mean of the squares between the actual and predicted values. Whereas MSE doesn't consider the root function. It is the moat used Loss or cost functions in the ML especially Regression, Classification, etc.
