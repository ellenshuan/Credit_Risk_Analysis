# Credit Risk Analysis

Overview of the loan prediction risk analysis:

The overview of this analysis is to explore oversampling and undersampling. Originally, we saw that there was a lot more samples in one category than the other which meant that the data heavily scewed towards one dataset. Therefore, we performed oversampling and undersampling to balance out the data in each category to perform a more accurate test and train. 


## Results

Accuracy score for oversampling

![](./Resources/oversampling.png)

Accuracy score for undersampling

![](./Resources/undersampling.png)

Accuracy score for undersampling and oversampling combination 

![](./Resources/combination.png)

Accuracy score for smote oversampling

![](./Resources/smote_oversampling.png)

Accuracy score for easy ensemble adaboost classifier 

![](./Resources/easy_ensemble_adaboost_classifier.png)

Accuracy score for balanced random forest classifier 

![](./Resources/balanced_random_forest_classifier.png)



## Summary

After looking at all of these sampling techniques, it is important to realize that the accuracy score for all of these techniques are lower than 70 precent. Also, it is important to note that it is only one percent higher of an accuracy score to undersample than to oversample. From these observations, we can conclude that it would be a wise choice to collect more data to get a higher accuracy score.

