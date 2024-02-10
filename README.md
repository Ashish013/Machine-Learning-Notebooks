# Machine-Learning-Notebooks

This repository contains code submitted for the final Machine Learning and Statistical Data Analysis coursework evaluation. The two problem statements selected for the courses are:

*i) Fetal health prediction*
*ii) Stroke prediction*

## Fetal health prediction
In this study, we first investigated various ways of dealing with significant data imbalances, such as basic under-sampling/over-sampling, the Synthetic Minority Oversampling Technique (SMOTE), and so on. After pre-processing the data and performing Explanatory Data Analysis (EDA), we investigated various machine learning techniques to identify foetal health, including logistic regression, Support Vector Machines with varied kernels, and decision trees. After selecting the baseline line model, a grid search cross-validation of multiple alternative hyper-parameter values yields an f-score of 0.98.


## Stroke prediction
In this project, we used a dataset containing 5110 data points to predict whether a patient will likely get a stroke based on attributes like past disease history, age and smoking status. First, we addressed the issue of heavy data imbalance in this project by applying SMOTE, followed by data pre-processing and EDA. We exposed it to various statistical tests and hypothesis testing to aid with data comprehension. After that, we trained the model on a random forest learning algorithm, achieving a 0.92 fscore on test data.
