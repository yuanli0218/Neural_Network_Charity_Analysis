# Neural_Network_Charity_Analysis

## Overview
This project is to use Neural Network to predict whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
IS_SUCCESSFUL is the target variable

EIN and NAME are neither targets nor features, but just for identification

All the other columns are potential features

### Compiling, Training, and Evaluating the Model
In the first model, I used two layers, one with 80 neurons and the second with 30 neurons. The activation function is relu for input layers and sigmoid for output layer. However, I failed to achieve the 75% target model performance.

Then I tried to optimize it by adding one more layer with 40 neurons and activation function changed to tanh. However, I still couldn't improve the model performance.

## Summary
Neural networks is very powerful and can potentially lead to overfitting. Maybe we should use other traditional models like random forests or SVM to see if better accurancy rate will be achieved.
