# SC1015 MiniProject - _Earthquake Damage Predictor_

## About

We aim to predict the level of damage to buildings caused by earthquakes based on aspects of building location and construction using dataset from 
[DRIVENDATA](https://www.drivendata.org/competitions/57/nepal-earthquake/page/135/) on the 2015 Gorkha earthquake in Nepal.<br>

Within this repository, you will find various data analysis and exploration techniques that can be used to identify key factors that contribute to earthquake damage. To gain a comprehensive understanding of the earthquake damage predictor, we recommend reviewing the source code in the following order:

1. [Data Extraction](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Logistic Regression](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Neural Network](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)

## Machine Learning Models

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Extreme Gradient Boosting (XGB)
5. K Nearest Neighbor

## Performance Metrics

<b>F1-Score (Micro)</b> and <b> Cohen's Kappa Score. </b>

## Conclusion

- Geographic Level (3,2,1) are the utmost important features in predicting damage grade<br>
- It is successful in helping hotel developers to reconstruct after the earthquake<br>
- The top-three best model performance is Extreme Gradient Boosting (XGB), Random Forest, and K-NN model<br>
- Not guaranteedly accurate, there is limitation due to the lack of knowledge and other missing features or consideration to take into account<br>

## Individual Contributions

- @jesdaniella - Neural Networks, Data Resampling, Data Extraction
- @ali-ad - Logistic Regression,  Data Visualization, Data Extraction

## References

- https://www.drivendata.org/competitions/57/nepal-earthquake/
- https://www.analyticssteps.com/blogs/how-does-linear-and-logistic-regression-work-machine-learning
- https://dataaspirant.com/catboost-algorithm/#t-1609567161998
- https://analyticsindiamag.com/7-types-classification-algorithms/
- https://dataaspirant.com/catboost-algorithm/#t-1609567161998
- https://medium.com/analytics-vidhya/richters-predictor-modeling-earthquake-damage-b44e3dbdaef
