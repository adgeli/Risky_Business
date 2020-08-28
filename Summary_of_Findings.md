# Risky Business: Findings Summary

![title_pic](Images/market_risk.jpg)

*This document reports a summary of the concluded findings in the Classification Unit 11 assignment.*

---

## Sections 

- [Risky Business: Resampling Techniques](#Resampling-Techniques)
- [Risky Business: Ensemble Learners](#Ensemble-Learners)

---

## Resampling Techniques

### Balanced Accuracy Score

![resampling_bas](Images/resampling_BAS.png)

The models with the best balanced accuracy score are SMOTE oversampling (99.48%) and Cluster Centroids undersampling (99.48%).

### Recall Score 

![resampling_rs](Images/resampling_RS.png)

The model with the best recall score is SMOTEENN. However, both oversampling models; Naive Random Oversampling and SMOTE have high recall scores as well.

### Geometric Mean Score

![resampling_gms](Images/resampling_gms.png)

The best geometric mean score are the oversmapling models; Naive Random Oversampling and SMOTE.

---

## Ensemble Learners

### Balanced Accuracy Score

![ensemble_bas](Images/ensemble_BAS.png)

The models with the best balanced accuracy score are the Niave Random Oversampling classifier and the Adaptive Boosting esemble learner.


### Recall Score 

![ensemble_rs](Images/ensemble_RS.png)

All models have an equal recall score.


### Geometric Mean Score

![ensemble_gms](Images/ensemble_gms.png)


All models have an equal geometric mean score.

### Top 3 Features

![features](Images/ensemble_3features.png)

---

