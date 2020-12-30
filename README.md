# Joseph_Tran_DS Portfolio
Data science portfolio


# [Capstone-project-2-Loan-default-predictor](https://github.com/JLtran11/Capstone_project_2)
The repository contains all the files associated with the second capstone project: Loan default prediction.

- Reduced large column space of anonymized features (755) via feature selection methods to create 3 data sets for modeling.
- Performed statistical analysis using qq plots for normality and t-tests for target class inference.
- Optimized logistic regression, adaboost, random forest, and xgboost using pipeline and random search to find optimal model
- Selected xgboost model for further tuning to optimize for reducing false negatives, reduce over-fitting to train data, and robustness   to imbalanced target class.

![](https://github.com/JLtran11/Joseph_Tran_DS_-Portfolio/blob/main/images/pca.png)
![](https://github.com/JLtran11/Joseph_Tran_DS_-Portfolio/blob/main/images/target.png)


# [Capston-Project-1-Music-recommendation-system](https://github.com/JLtran11/Capston-Project-1-Music-recommendation-system)
The repository contains all the files associated with the first capstone project

- Utilized the nowplaying-rs dataset of over 17 million listening events to build music recommender system.
- Cleaned and merged three separate tables with pandas to facilitate analysis amd modeling.
- Conducted time series analysis to investigate individual and cohort listening habits, and identify anomolies.
- Constructed user/item sparse matrix object of shape (21220,81343) for algorithm.
- Utilized ALS and Lightfm packages to build two recommenders for comparison with popular (most common) recommendations.
- Models evaluated with AUC for performance comparison : ALS: 0.916, popularity: 0.875, lightfm: 0.937

![](https://github.com/JLtran11/Joseph_Tran_DS_-Portfolio/blob/main/images/loglisten.PNG)
![](https://github.com/JLtran11/Joseph_Tran_DS_-Portfolio/blob/main/images/listen_count.PNG)
