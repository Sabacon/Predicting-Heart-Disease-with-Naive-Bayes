# Predicting Heart Disease with Naive Bayes

## Background
Naive Bayes is a supervised classification algorithm based on Bayes' theorem. `Bayes' theorem` aims to find the probability of an event A occurring given another even B is True.

Naive Bayes works on two assumptions:
* `conditional independence` - each predictor variable is independent from the other, conditioned on class. Two variables can only be conditionally independent of each other when considered in relation to a third variable.
* `equal predictive power` - no predictor variable has more predictive power than any other predictor.

Both assumptions are often violated. Very few datasets in the real world satisfy them. Naive Bayes performs well regardless.

## Problem
I want to predict the presence or absence of heart disease in patients based on blood pressure, resting blood pressure, cholesterol etc.

## Data
The data used has 303 observations and 14 features. It is available in this repository.

## Tools
* pandas
* numpy
* matplotlib/seaborn
* scikit-learn
* naive bayes

For more, check out the notebook.
