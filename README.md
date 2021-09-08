# Machine-Learning-Notebooks

This repository contains code submitted for the final evaluation of Machine Learning and Statistical Data Analysis coursework's. The two problem statements selected for the courses respectively are:

*i) Fetal health prediction*

*ii) Stroke predicition*

## Fetal health prediction

In this study, we first investigated various ways for dealing with significant data imbalances in the data, such as basic under-sampling/over-sampling, the Synthetic Minority Oversampling Technique (SMOTE), and so on. After pre-processing the data and performing Explanatory Data Analysis (EDA), we investigated a wide range of machine learning techniques to identify foetal health, including logistic regression, Support Vector Machines with varied kernels, and decision trees. After selecting the baseline line model, a grid search cross-validation of multiple alternative hyper-parameter values is done, yielding an f-score of 0.98.


## Stroke prediciton

In this project, we used a dataset containing 5110 data points to predict whether a patient will likely get a stroke based on attributes like past diseases history, age and smoking status. We addressed the issue of heavy data imbalance foremost in this project by applying SMOTE, followed by data pre-processing and EDA. To aid with data comprehension, we exposed it to a range of statistical tests and hypothesis testing. After that, we trained the model on a random forest learning algorithm, achieving a 0.92 fscore on test data.
