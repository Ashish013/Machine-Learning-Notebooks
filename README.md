# Machine-Learning-Notebooks

This repository contains code submitted for the final evaluation of Machine Learning, Statistical data analysis coursework's. The two problem statements selected for the courses respectively are:

i) Fetal health prediction
ii) Stroke predicition

## Fetal health prediction

In this project, we first explored different strategies to tackle the severe data imbalance in the data using simple under-sampling/over-sampling, Synthetic Minority Oversampling Technique (SMOTE) etc.
Then after pre-processing the data and conducting Explanatory Data Analysis (EDA), we explored an exhaustive list of different machine learning algorithms such as logistic regression, Support Vector Machines with varying kernels and decision trees to classify the foetal health.
Following the selection of the baseline line model, a Grid search cross-validation of several alternative hyper-parameter values is performed to choose the best possible model from the exhaustive algorithm pool, achieving an f-score value of 0.98.

## Stroke prediciton

In this project, we first handled the issue of heavy data imbalance, followed by data pre-processing and EDA. The data is then subjected to a variety of statistical tests and hypothesis testing to aid in data understanding. The model is then trained using a random forest learning algorithm, which achieves a 0.92 fscore on test data.
