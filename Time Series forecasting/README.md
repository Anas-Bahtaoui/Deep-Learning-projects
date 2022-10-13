### Time Series Forcasting

Challenges done as part of the course of Artificial Neural Networks and Deep Learning 2021/2022

https://codalab.lisn.upsaclay.fr/competitions/621


## Artificial Neural Networks and Deep Learning 2021 - Second Homework
## Time Series Forecasting
Welcome to the second Homework of the Artificial Neural Networks and Deep Learning course! You have the opportunity to test what you learned during the course. We set up a competition to make things more fun! 😎

In this homework, you are required to predict future samples of a multivariate time series. The goal is to design and implement forecasting models to learn how to exploit past observations in the input sequence to correctly predict the future. 

## Homework Evaluation
The competition consists of a multivariate time series forecasting problem. Thus, you must provide a prediction for each time step in the test prediction window.

Only the training set is given. The test set is not provided. You must submit directly your code for evaluation.
The metric used to evaluate models and place the Teams in Leaderboard is the Root Mean Squared Error (RMSE). The score is computed as:

$$ RMSE = \sqrt{\sum_{i = 1}^n \frac{(\hat{y_i} - y_i)^2}{n}} $$

where n is the total number of samples in the test prediction window. Being multivariate forecasting, the total RMSE is computed considering all the samples in the test window from all the features in the multivariate problem.
