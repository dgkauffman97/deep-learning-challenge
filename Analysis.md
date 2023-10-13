# deep-learning-challenge

## Overview
The purpose of this analysis was to predict whether an oragnization will be successful if they receive funding from Alphabet Soup. This was done by looking at metadata from over 34,000 previously funded organizations, indluding application type, classification, amount of funding requested, income amount, and more. This data was used to train a neural network model to predict the success of future funding.

## Results

### Data Pre-processing
The target variable for the model is "IS_SUCCESSFUL." Two columns were dropped from the dataset because they were neither targets nor features: "EIN" and "NAME."

### Compiling, Training, and Evaluating the Model
I chose two to three layers and some combination of the tanh and relu activation functions. Neurons ranged from 2 to 20, but were generally under 10. I was unable to achieve target model performance, though I was able to improve accuracy from 71.92% to 72.89% over the course of five attempts.

## Summary
Overall, the neural network model was able to predict the success of a funded organization at 72.89% accuracy. Another way to approach this task could be a supervised learning model like a logistic regression.