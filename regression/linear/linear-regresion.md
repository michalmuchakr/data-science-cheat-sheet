# Linear Regression

Linear regression is a supervised machine learning algorithm used for predicting a continuous target variable based on one or more predictor variables. It assumes a linear relationship between the predictor(s) and the target variable. The simple linear regression model can be expressed as:

## Simple Linear Regression

In simple linear regression, we have one predictor variable (X) and one target variable (Y). The model can be represented as:

\[ Y = \beta_0 + \beta_1X + \epsilon \]

Where:
- \( Y \) is the target variable we want to predict.
- \( X \) is the predictor variable.
- \( \beta_0 \) is the intercept (constant term).
- \( \beta_1 \) is the coefficient for the predictor variable.
- \( \epsilon \) is the error term, representing the residual or unexplained variation.

The goal in simple linear regression is to estimate the values of \( \beta_0 \) and \( \beta_1 \) that minimize the sum of squared errors (SSE) or mean squared error (MSE).

## Multiple Linear Regression

In multiple linear regression, we have more than one predictor variable. The model can be extended as follows:

\[ Y = \beta_0 + \beta_1X_1 + \beta_2X_2 + \ldots + \beta_pX_p + \epsilon \]

Where:
- \( Y \) is still the target variable.
- \( X_1, X_2, \ldots, X_p \) are the predictor variables.
- \( \beta_0 \) is the intercept.
- \( \beta_1, \beta_2, \ldots, \beta_p \) are the coefficients for the predictor variables.
- \( \epsilon \) represents the error term.

The goal in multiple linear regression is to estimate the values of \( \beta_0, \beta_1, \beta_2, \ldots, \beta_p \) that minimize the SSE or MSE.

## Conclusion

Linear regression is a fundamental tool in statistics and machine learning for modeling the relationship between variables. It provides a simple yet powerful way to make predictions and understand the influence of predictor variables on the target variable.

