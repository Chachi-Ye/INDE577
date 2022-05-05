---

## K Nearest Neighbors

The k-nearest neighbors (KNN) algorithm is a data classification method for estimating the likelihood that a data point will become a member of one group or another based on what group the data points nearest to it belong to.

The k-nearest neighbor algorithm is a type of supervised machine learning algorithm used to solve classification and regression problems. However, it's mainly used for classification problems.

It's considered a non-parametric method because it doesn’t make any assumptions about the underlying data distribution. Simply put, KNN tries to determine what group a data point belongs to by looking at the data points around it.

## Objectives

In this project, I will build a KNN model with the classification errors by Euclidean distance. Also, I will build a function to choose the optional K by the classification errors.

## Data

The dataset used for this model is a public data from Kaggle, https://www.kaggle.com/datasets/sveneschlbeck/beginners-classification-dataset

The dataset contains only three columns:

age

interest: the value of how people are interested in learning new sport

success: "1" represents success, "0" represents fail.
 
The content can be applied to various things, e.g. how successful different people learn new sports.

## Packages
Pandas https://pandas.pydata.org/
Matplotlib https://matplotlib.org/
Numpy https://numpy.org/
Seaborn https://seaborn.pydata.org/
Scikit-learn https://scikit-learn.org/
