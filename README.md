# Why use a regression algorithm?

- Regression algorithms are used in machine learning to predict continuous values, such as stock prices.

## How does that work?
- Regression is useful for identifying and modeling the relationship between a dependent variable (In this case the stock price) and one or more independent variables (historical prices, dates, volume etc.)
- Unlike classification algorithms, which predict categorical outcomes, regression algorithms are designed to predict quanatative values. Since stock prices are continuous and quantative, regression is the CORRECT type of algorithm to use.
- There are several different type of regression algorithms that can handle different levels of complexity in the data. For example, a linear regression algorithm may fit simple linear trends while more complex methods may capture non-linear patterns.

## What do we use in this project and why?
In our project we first look at a linear model, which naturally is a bit simple for the data. We then move on to a polynomial model, which seems to fit the data much better. In the end we try to combine the polyomial model with Ridge regression, which in our case turns out to fit our data even better.
- Going from a linear to a polynomial and the adding Rigde regression is an iterative approach in model building.
- We start with the simplest, move on to more complex, and introduce regularization to get a robust model that can generalize well.
- This is a methodology for fine-tuning the model's complexity against its ability to perform well on data it has not seen before, which is essential in machine learning.