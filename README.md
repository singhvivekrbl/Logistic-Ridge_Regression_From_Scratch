# Logistic-Ridge_Regression_From_Scratch

The goal of repository is to practice performing data analysis, implementing logistic classification, and understanding the practical implementation of different regression models.

1 Provide brief details about the nature of your dataset. What is it about? What type of data are we encountering? How many entries and variables does the dataset comprise?
2. Provide the main statistics about the entries of the dataset (mean, std, number of missing values, etc.)
3. Visualize the data (provide at least 5 graphs), e.g. correlations between different features. Are there any interesting patterns?

## Logistic Regression

In this part we will work on logistic regression and will use a logistic function to model a binomial (Binary / Bernoulli) output variable. Logistic regression model predicts that the observation belongs to a particular category. To generate these probabilities, logistic regression uses the sigmoid function. This function maps a real number to a value between 0 and 1.

Steps:
1. Choose ONE dataset from the provided list in Part I.
2. Calculate the weight vector (w) using the Ordinary Least Squares (OLS) estimate.
3. Using the weight vector (w) you computed, identify the predictions for the test data.
4. Calculate the mean squared error for the test dataset.
5. Create a plot comparing the predictions vs the actual test data targets

## Ridge Regression

Steps:
1. Calculate the weight vector (w) by direct minimization.
2. Using the weight vector (w) you computed, identify the predictions for the test data.
3. Calculate the RMSE for the test dataset.
4. Create a plot comparing the predictions vs the actual test data targets.
