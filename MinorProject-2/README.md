# MinorProject-2

## Theory Questions

### Question-1: When should you use classification over regression?

**Answer:** If we want to predict a particular class or discrete values we must use classification. It can be either binary or multiclass classification but the output will be some category. Regression has to be used when we have to predict the continuous outcome rather than predicting to which class it belongs as in the case of Classification.
For example, if we consider the IRIS Flower problem we need to predict to which class/group does the flower belongs. Here the number of classes is three.
Similarly, if we consider the MNIST data our ultimate outcome is to predict to which class/group the handwritten digit belongs to which ranges from digits (1-9) belong.
<hr>

### Question-2: How do you deal with the class imbalance in a classification problem?

**Answer:** There are various ways through which we can deal with the above problem i.e. Class imbalance in Classification problem:
>Selecting appropriate Dataset

>Selecting appropriate subset or in correct proportion

>Using Random Sampling

>Using Ensemble Methods

>Cleaning the Data appropriately

>Cluster-Based Approach (changing the number of clusters)
><hr>

### Question-3: What is a confusion matrix and why do you need it?

**Answer:** ![image](https://user-images.githubusercontent.com/81156510/129568018-6ebeba18-fbf8-4603-bf8c-62b992084a50.png)

A Confusion Matrix is a 2D matrix containing data that gives information about a Classification Algorithm. From a Confusion Matrix, we can determine the accuracy, recall, precision, and F1 score of the model developed using the Classification Algorithm. For a multi-class classification problem, we have a 2X2 matrix. We have 4 terms associated with it namely True Positive, True Negative, False Positive, and False Negative. From the confusion matrix, we can derive 4 different metrics as mentioned above and are based on Actual and Predicted values.
<hr>

### Question-4: What is the difference between sigmoid and softmax function?

**Answer:**
*Sigmoid Function:* ![image](https://user-images.githubusercontent.com/81156510/129568411-adb61161-b2f1-4bb9-afcd-6f22dd10fc4f.png)

It is one of the activation functions used in DL where the predicted Output remains in the range of 0 to 1. It is also called s logistic function or logistic sigmoid function. It can be used both in Regression as well as Classification problems. It has another use as well that it can converge fast as well hence improves the fastness towards Gradient Descent.

*Softmax Function:* ![image](https://user-images.githubusercontent.com/81156510/129568454-338cd441-ef3c-4ee9-a003-cafdfabbdbcf.png)

It is a function that turns a vector of K real values into a vector of K real values that adds to 1. Input can be in any range either positive, negative, or zero but the softmax converts them to values between 0 and 1, which can be considered as probabilities.
<hr>
