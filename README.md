# ML-Challenge

HackerEarth organised a Machine Learning challenge from June 9 to June 30, 2020. 
It was a regression problem, the task was to predict the attrition rate of employees of an organization based on some given features. 

I have attached the data in this repository. 

## My approach

I used correlation matrix to remove irrelevant features. 
Imputed the feature data like Age with mode values. 
For all the relevant categorical data, I used one hot encoder. 

After trying regression models like decision tree and random forest, I decided to use Neural networks for the problem.
It gave much better result but still the performance was quite bad, I then optimised the hyperparameters and did some feature engineering. 
The final accuracy score was 81.307. 
The best model got accuracy score of 81.699. 

## Result
I got a rank of 54/5146 participants. As this was my first Machine Learning Challenge, I am more than satisified with the result. 

### Link for the contest for practice
[HackerEarth Machine Learning Challenge](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-employee-attrition-rate/problems/)
