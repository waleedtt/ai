# AI Study
AI study

## Regressions
* Simple Linear Regression

Simple linear regression is a statistical method used to examine the relationship between two continuous variables: one independent variable (predictor) and one dependent variable (response). The primary goal is to model the relationship between these variables by fitting a linear equation to the observed data.

y= b0 + b1X
dependent variable = y-intercept(constant) + slope coefficient independent

* Multiple Linear Regression

Multiple linear regression refers to a statistical technique that is used to predict the outcome of a variable based on the value of two or more variables. It is sometimes known simply as multiple regression, and it is an extension of linear regression. The variable that we want to predict is known as the dependent variable, while the variables we use to predict the value of the dependent variable are known as independent or explanatory variables.
Y = b0 + b1X1 + b2X2

Where:

y is the dependent or predicted variable
b0 is the y-intercept, i.e., the value of y when both xi and x2 are 0.
b1 and b2 are the regression coefficients representing the change in y relative to a one-unit change in xi1 and xi2, respectively.


* Polynomial Regression

Polynomial regression is an extension of simple linear regression that allows for modeling the relationship between the independent variable (X) and the dependent variable (Y) as an nth degree polynomial. This approach can capture more complex, non-linear relationships that a simple linear regression might miss.


* Support Vector Regression

Support Vector Regression (SVR) is a type of machine learning model that applies the principles of Support Vector Machines (SVM) to regression problems. Unlike traditional linear regression, SVR uses a margin of tolerance (epsilon) and kernel functions to handle non-linear relationships between the independent variable (features) and the dependent variable (target).

* Decision Tree Regression

Decision Tree Regression is a non-linear regression technique that uses a decision tree to model the relationship between the independent variables (features) and the dependent variable (target). The model splits the data into subsets based on feature values, creating a tree-like structure of decisions, which makes it highly interpretable and capable of capturing complex patterns in the data.

* Random Forest Regression

Random Forest Regression is an ensemble learning method that combines multiple decision trees to improve the predictive performance and robustness over that of a single decision tree. By aggregating the predictions of many trees, random forest aims to reduce overfitting and increase the accuracy and stability of the regression model.

* Evaluating Regression Models

    * R-squared

        R-squared also known as the coefficient of determination, is a statistical measure used to evaluate the goodness of fit of a regression model. It represents the proportion of the variance in the dependent variable that is predictable from the independent variables. In simpler terms, R-squared indicates how well the independent variables explain the variation in the dependent variable.

    * Adjusted R-squared

        Adjusted R-squared  is a modification of R-squared that accounts for the number of predictors in a regression model. It adjusts the value based on the number of predictors and the number of observations, providing a more accurate measure of model fit, particularly in multiple regression where the model includes several predictors.
