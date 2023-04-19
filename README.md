# Parameter Optimization of SVM

Assignment for UCS654

## About SVM and Parameter Optimization

One of the most well-liked supervised learning algorithms, Support Vector Machine, or SVM, is used to solve Classification and Regression issues. However, it is largely used in Machine Learning Classification issues.

It is possible to alter several of the most crucial SVM parameters, including kernel, C, and gamma, to increase accuracy. Hyperparameter tuning is the term used for this.

GridSearchCV may be used for this purpose to optimize these settings.

I've used a Fitness Function in this Python program to optimize the settings.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

## Final Result Table

    Sample	Best Accuracy	Best Kernel	Best Nu	Best Epsilon

0 1 0.91 linear 7.41 3.05
1 2 0.95 linear 0.92 1.02
2 3 0.86 linear 1.34 7.71
3 4 0.95 rbf 3.82 0.26
4 5 0.93 linear 10.00 2.87
5 6 0.94 linear 2.50 0.19
6 7 0.92 poly 1.52 4.62
7 8 0.93 poly 0.61 7.88
8 9 0.92 linear 1.55 5.61
9 10 0.88 poly 1.07 0.38

## Written By

Name : Jatin Goyal

Roll No. : 102003307

Sub-Group: 3CO12
