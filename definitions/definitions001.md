# My notes

## Data science life cycle: 

formulate question
gather question 
clean Data: missing, incomplete, inaccurate, formatting, etc 
explore and visualize
train algorithm
evaluate 
_____________________________
## Linear Regression: Why slope?
Is a statistical method to find a relationship between one dependent and one or more independent variables

The strong the relationship the stronger the slope
The weak the relationship the flat the slope

The relationship between dependent and independent must be linear. With the help of scatterplot it can be detected.
_____________________________
## Residuals
The gap between the actual and the predicted value.
Looks at the size and choose the ones that have the less residuals.
_____________________________
## Coefficients and intercepts
Rational: [examples](https://www.austincc.edu/mparker/1342/lessons/less5-8/interpret_slope.pdf)
_____________________________
## detect outliers
with histogram and boxplot
_____________________________
## homoscedasticity
the situation in which the variance of the dependent variable is same for all the data
_____________________________
## intercept and coefficient 
[source](https://support.minitab.com/en-us/minitab-express/1/help-and-how-to/modeling-statistics/regression/supporting-topics/regression-models/slope-and-intercept-of-the-regression-line/)

regression.intercept_ = if it is a positive number, this much will increase if a one point increases in 'x' variable
regression.coefficient_ = if it is a negative value, this much will decrease if the 'x' variable is 0.

![y=mx+c](../images/y=mx+c.png)
_____________________________
## R2 (rsquare)
this measures the relationship between the model and the dependent variable on a scale of 0-100%.
_____________________________
## algorithm
this is a ML process does. 
![y=mx+c](../images/algorithm.png)
_____________________________
## RSS (residual sum of squares)
The lower the number the better the line and the estimates for this coefficients. 
_____________________________
## Gradient Descent
This algorithm is used in order to draw a regression line(predicted values) using the minimum error( slope and intercept). An iterative model
is built until the rate of error is the least. (This topic needs to revisited often)
[source](https://medium.com/code-heroku/gradient-descent-for-machine-learning-3d871fa48b4c)
_____________________________
## How to convert categorical data to numerical?
Integer(label) encoding and One hot encoding
Label encoding is done on the discrete values, converted to numbers
In One hot encoding, a variable is removed and added as a new binary variable for each variable that is removed
_____________________________
## 







