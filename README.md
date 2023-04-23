# SC1015 MiniProject - _Earthquake Damage Predictor_

Tutorial Group : B125<br>
Instructor : Dr Smitha and Ong Chin Ann<br>

## About

We aim to predict the most important features that affects the level of damage (damage grade) to buildings caused by earthquakes based on aspects of building location and construction using dataset from 
[DRIVENDATA](https://www.drivendata.org/competitions/57/nepal-earthquake/page/135/) on the 2015 Gorkha earthquake in Nepal.<br>

Within this repository, you will find various data analysis and exploration techniques that can be used to identify key factors that contribute to earthquake damage. To gain a comprehensive understanding of the earthquake damage predictor, we recommend reviewing the source code in the following order:

1. [Data Extraction](https://github.com/ali-adi/SC1015-Mini-Project/blob/main/Data%20Extraction%20and%20Preparation%20(1).ipynb)
2. [Data Cleaning]()
3. [Exploratory Data Analysis]()
4. [Machine Learning](https://github.com/ali-adi/SC1015-Mini-Project/blob/main/Machine%20Learning%20Models%20(1).ipynb)
5. [Conclusion](https://github.com/ali-adi/SC1015-Mini-Project/blob/main/Conclusion%20(2).ipynb)

## The Dataset

The data is used in a competition hosted by drivendata.com "Richter's Predictor: Modeling Earthquake Damage." A destructive earthquake of 7.8 magnitude occured in Nepal in April 2015. This earthquake claimed almost 9,000 lives and around $10 billion in damages. Millions of people lost everything and became homeless in a few moments.

Reference: https://www.drivendata.org/competitions/57/nepal-earthquake/page/135/

## Problem Formulation
Problem: Which characteristics of buildings are most relevant in predicting whether it will withstand earthquakes?

The objective of this project is to see how each buildings' features and variables affects their damage grade in the case of an earthquake and determine whch ones have the highest correlation to it. By finding the most important features, we can help developers during reconstruction so that they can apply corrections to their structure, especially on these characteristics, and minimize their risk of experiencing the same level of danger and damage in the case of another earthquake. We are going to do this by using 4 different machine learning models. 

## Machine Learning Models

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Extreme Gradient Boosting (XGB)

## Performance Metrics

<b>F1-Score (Micro)</b> 

## Conclusion

- Foundation and ground floor type are the most important features in predicting damage grade.<br>
- We think that this will be successful in helping hotel developers to reconstruct after the earthquake<br>
- The best model performance is <b>Extreme Gradient Boosting</b> (XGB)<br>
- This is not guaranteed in terms of accuracy since there are still limitations to our model such as lack of knowledge and other missing consideration that have not been taken into account<br>
- From Exploratory Data Analysis, we found that only 9.64% building that has low Damage level, the rest is 56.89% building has Medium Damage level, and 33.47% building has High Damage level<br>

## Individual Contributions

- @jesdaniella -  Extreme Gradient Boosting, Random Forest, Performance Metrics (F1- Scores)
- @ali-ad - Logistic Regression, Decision Tree, Data extraction

## References

- https://www.drivendata.org/competitions/57/nepal-earthquake/
- https://www.analyticssteps.com/blogs/how-does-linear-and-logistic-regression-work-machine-learning
- https://dataaspirant.com/catboost-algorithm/#t-1609567161998
- https://analyticsindiamag.com/7-types-classification-algorithms/
- https://dataaspirant.com/catboost-algorithm/#t-1609567161998
- https://medium.com/analytics-vidhya/richters-predictor-modeling-earthquake-damage-b44e3dbdaef
