# Boston Housing Regression Project

This project aims to predict the median value of owner-occupied homes in the Boston area using various regression techniques on the Boston Housing dataset. The dataset contains 506 samples with 13 features and a target variable (median home value).

## Dataset Description

The dataset consists of the following features:

1. CRIM - per capita crime rate by town
2. ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS - proportion of non-retail business acres per town
4. CHAS - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX - nitric oxides concentration (parts per 10 million)
6. RM - average number of rooms per dwelling
7. AGE - proportion of owner-occupied units built prior to 1940
8. DIS - weighted distances to five Boston employment centers
9. RAD - index of accessibility to radial highways
10. TAX - full-value property-tax rate per $10,000
11. PTRATIO - pupil-teacher ratio by town
12. B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13. LSTAT - % lower status of the population

Target Variable:
- MEDV - Median value of owner-occupied homes in $1000's

## Regression Models

the regression model implemented and evaluated for this project:
- Lasso Regression with LassoCV

## Model Evaluation

Model performance was evaluated using the following metrics:

- Mean Squared Error (MSE)
- R-squared
