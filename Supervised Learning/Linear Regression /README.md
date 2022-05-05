---

## Linear Regression

Linear regression is a linear model, e.g. a model that assumes a linear relationship between the input variables (x) and the single output variable (y). More specifically, that y can be calculated from a linear combination of the input variables x. It is both a statistical algorithm and a machine learning algorithm.

## Objectives

In this project, we will build a linear regression model of the normal class data with "pelvic_incidence" and "sacral_slope" features.

## Data

The dataset used for this model is a public data from Kaggle, https://www.kaggle.com/datasets/uciml/biomechanical-features-of-orthopedic-patients

For the second task, the categories Disk Hernia and Spondylolisthesis were merged into a single category labelled as 'abnormal'. Thus, the second task consists in classifying patients as belonging to one out of two categories: Normal (100 patients) or Abnormal (210 patients).

Each patient is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (each one is a column):

pelvic incidence
pelvic tilt
lumbar lordosis angle
sacral slope
pelvic radius
grade of spondylolisthesis

## Packages
Pandas https://pandas.pydata.org/
Matplotlib https://matplotlib.org/
Numpy https://numpy.org/
Seaborn https://seaborn.pydata.org/