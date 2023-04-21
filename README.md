# SC1015 MiniProject - _Earthquake Damage Predictor_

Tutorial Group : B125<br>
Lecturer : Dr Smitha<br>
Chosen Dataset : <br>

## About

We aim to predict the level of damage to buildings caused by earthquakes based on aspects of building location and construction using dataset from 
[DRIVENDATA](https://www.drivendata.org/competitions/57/nepal-earthquake/page/135/) on the 2015 Gorkha earthquake in Nepal.<br>

Within this repository, you will find various data analysis and exploration techniques that can be used to identify key factors that contribute to earthquake damage. To gain a comprehensive understanding of the earthquake damage predictor, we recommend reviewing the source code in the following order:

1. [Data Extraction]()
2. [Data Visualization]()
3. [Data Resampling and Splitting]()
4. [Logistic Regression](the ipynbs)
5. [Neural Network]()

## The Dataset

The data is used in a competition hosted by drivendata.com "Richter's Predictor: Modeling Earthquake Damage." A destructive earthquake of 7.8 magnitude occured in Nepal in April 2015. This earthquake claimed almost 9,000 lives and around $10 billion in damages. Millions of people lost everything and became homeless in a few moments.

Reference: https://www.drivendata.org/competitions/57/nepal-earthquake/page/135/

## Problem Formulation
Problem: Which proposed hotel buildings are safe enough to withstand earthquakes and which ones are not?

The objective of this project is to classify hotels as either safe or dangerous in the case of an earthquake by finding the most optimal and relevant feature using machine learning models to be used as predictor.


## Machine Learning Models

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Extreme Gradient Boosting (XGB)
5. K Nearest Neighbor

## Performance Metrics

<b>F1-Score (Micro)</b> and <b> Cohen's Kappa Score. </b>

## Conclusion

- Geographic Level (3,2,1) are the first most important features in predicting damage grade and following that is the building's Age<br>
- Based on our final test, we think that this will be successful in helping hotel developers to reconstruct after the earthquake<br>
- The top-three best model performance is Extreme Gradient Boosting (XGB), Random Forest, and K-NN model<br>
- This is not guaranteed in terms of accuracy since there are still limitations to our model such as lack of knowledge and other missing consideration that have not been taken into account<br>
- From Exploratory Data Analysis, we found that only 9.64% building that has low Damage level, the rest is 56.89% building has Medium Damage level, and 33.47% building has High Damage level<br>

## Individual Contributions

- @jesdaniella -  Extreme Gradient Boosting, K-Nearest Neighbors, Random Forest
- @ali-ad - Logistic Regression, Decision Tree, Data extraction

## References

- https://www.drivendata.org/competitions/57/nepal-earthquake/
- https://www.analyticssteps.com/blogs/how-does-linear-and-logistic-regression-work-machine-learning
- https://dataaspirant.com/catboost-algorithm/#t-1609567161998
- https://analyticsindiamag.com/7-types-classification-algorithms/
- https://dataaspirant.com/catboost-algorithm/#t-1609567161998
- https://medium.com/analytics-vidhya/richters-predictor-modeling-earthquake-damage-b44e3dbdaef
