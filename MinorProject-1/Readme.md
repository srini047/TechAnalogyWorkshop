# MinorProject-1

## Dataset Link: https://s3.us-west-2.amazonaws.com/public.gamelab.fun/dataset/salary_d


## Reference: https://towardsdatascience.com/machine-learning-simple-linear-regression-with-python-f04ecfdadc13

## Code: https://github.com/srini047/TechAnalogyWorkshop/blob/main/MinorProject-1/project-1.ipynb

### Theory Questions

<hr></hr>

**Question 1: What is overfitting and how to avoid it?**

***Answer:*** It is a condition where the model fits and performs very well in Training Data but when it comes to Unseen Data(Testing) it doesn't performs well. It would be a highly biased prediction and we will not be able to get the desired results.

We can avoid overfitting by tuning the hyperparameters, reducing the learning rate, changing the ratio of train and test data set, tuning the model to a generalised prediction, improving the quality of the dataset by cleaning the dataset and much more ways can helps in reducing Overfitting.

![image](https://user-images.githubusercontent.com/81156510/129439182-9f30f508-29a9-48af-a1d7-53aca9e0960e.png)

<hr></hr>

**Question 2: What is RMSE and MSE? How can you calculate them?**

***Answer:*** 

*RMSE:* Root Mean Square Error

*MSE:* Mean Squared Error

They are loss or cost functions whcih are used to estimate the correctness or working of a model. RMSE takes the root of the mean of the squares between the actual and predicted values. Whereas MSE doesn't consider the root function. It is the moat used Loss or cost functions in the ML especially Regression, Classification, etc.

![image](https://user-images.githubusercontent.com/81156510/129439170-26f62219-327c-4f9a-9cd5-946d40b6fa17.png)

<hr></hr>

**Question 3: What is Line of best fit?**

***Answer:*** In Regression the Best-Fit line is the one where the sum of distance between the Best-Fit Line and Data Points is minimum is called the Line of Best-Fit. The distance has to be minimum because only then the Loss Functon will reduce and we can have a more better model.

But in the case of Classification, the Best-Fit Line is the one where the Distance between the Best-Fit line and the Data points have to be maximum. The reason is that as the distance increases the Classification becomes easier and we can have a better model and predict correctly if a new data-point enters.

<hr></hr>

**Question 4: Explain multivariant linear regression using a real-life example.**

***Answer:*** It is a supervised ML Algorithm which uses multiple data-variables for Analysis. It is similar to Multiple Regression but an extension of it where one dependent variable and many independent variables are used to build the model and predict the output. There are various real-world examples like if we want to predict the price of the house we consider diferent factors like (area, location, no.of rooms, floors, facilitied) independent variables and (price) dependent variable. Then if we want to know the users interest we look into users past history which contains various data-variables and taking that into consideration we come to a conclusion regarding users interest. These are a few examplea but there are many which is difficult to list all of them.

**Question 5: How can we improve the accuracy of a linear regression model?**

***Answer:*** We can increase the acuuracy of the Linear Regression Model by the following ways:

> Data Cleaning (Outlier Removal)

> Feature Engineering (getting new column from existing data)

> Feature Selection (selecting required independent variables)

> Adding more data points

> Spliiting the Train and Test Dataset Differently.

> Using Multiple Algorithms

> Tuning Algorithms (Hyperparameter Tuning)

> Using Ensemble Methods

> Using Cross Validation

<hr></hr>
