BISI CST2208 w23 Project is analyzing different aspects of Diabetes in the Pima Indians tribe by doing Exploratory Data Analysis and building a classification Model.
Pima Diabetes Data Analytics – Neil¶
Here are the set the analytics that has been run on this data set
Data Cleaning to remove zeros
Data Exploration for Y and Xs
Descriptive Statistics – Numerical Summary and Graphical (Histograms) for all variables
Screening of variables by segmenting them by Outcome
Check for normality of dataset
Study bivariate relationship between variables using pair plots, correlation and heat map
Statistical screening using Logistic Regression
Validation of the model its precision and ploting of confusion matrix
Importing necessary packages¶
In [2]:
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
sns.set(color_codes =True)
%matplotlib inline
