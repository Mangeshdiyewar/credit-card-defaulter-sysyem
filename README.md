# credit-card-defaulter-sysyem

**Project Name**

Credit Card Default Prediction Using various Machine learning Algorithms

**Overview**

This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month
credit card defaulter based on demographic and last six months behavioral data of customers.

**ENVIRONMENT**

The analysis has been fully conducted with Python language, exploiting several machine learning and statistical
frameworks available such as scikit-learn, numpy, pandas, imblearn together with other data visualization libraries (
matplotlib and seaborn).

**Data Origin**

This project based on a dataset by I-Cheng Yeh (2019), Department of Information Management, Chung Hua University,
Taiwan on a UCI Machine Learning Repository
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
description of the data and the variables values can be found in the UCI data page with the attached link.

**Analysis Description**

**note:** before the start download the data from the attached link then rename and change it's type to 'default-1.csv'
then upload it to the shell you work with

Step 1 – simple data exploration using means of all the variables by defaulted person against not defaulted. also a
correlation matrix between all the variables to find variables with strong correlation that can be reduced. And a linear
regression to explore how strong is the correlation of independent variables (features) to the dependent variable (
default).
Step 2 - clustering of the data with kMEANS Clustering and forming 3 different clusters
Step 3 – fitting each cluster with different Machine learning algorithms to train the model and best model will be
selected for each cluster:

    Gaussian naive Bayes (GaussianNB)
    XGBoost Classifier
	Random Forest Classifier (RFC)

Step 4 – out of these 3 models the best model will get selected for that cluster and these trained models will sent for
testing

**TECHNOLOGIES USED**

Azure Travis Codecov CircleCI Nightly wheels Black PythonVersion PyPi DOI Benchmark

https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.png
scikit-learn is a Python module for machine learning built on top of SciPy and is distributed under the 3-Clause BSD
license.

The project was started in 2007 by David Cournapeau as a Google Summer of Code project, and since then many volunteers
have contributed. See the About us page for a list of core contributors.

It is currently maintained by a team of volunteers.

Website: https://scikit-learn.org

Installation
Dependencies
scikit-learn requires:

Python (>= 3.8)

NumPy (>= 1.17.3)

SciPy (>= 1.3.2)

joblib (>= 1.0.0)

threadpoolctl (>= 2.0.0)

