---

## Decision and Regression Tree

Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.

## Objectives

In this project, we will implement decision trees of classification and regression with different dataset by the Scikit-learn package. Also we will evaluate our models performance on the testing data by confusion matrix and accuracy scores.

## Data

### Classification

The dataset used for this model is a public data from Kaggle, https://www.kaggle.com/datasets/sveneschlbeck/beginners-classification-dataset

The dataset contains only three columns:

age

interest: the value of how people are interested in learning new sport

success: "1" represents success, "0" represents fail.
 
The content can be applied to various things, e.g. how successful different people learn new sports.

### Regression

The regression data is the generated quadratic data with white noise.

## Packages
Pandas https://pandas.pydata.org/
Matplotlib https://matplotlib.org/
Numpy https://numpy.org/
Seaborn https://seaborn.pydata.org/
Scikit-learn https://scikit-learn.org/
