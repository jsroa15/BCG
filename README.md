# Virtual Experience BCG

This repository contains my work on the virtual experience with BCG GAMMA.

Thanks to Ken Jee for provide a general framework to document projects on GitHub. Visit https://github.com/PlayingNumbers/ds_salary_proj#web-scraping
and https://www.youtube.com/watch?v=MpF9HENQjDo&list=PL2zq7klxX5ASFejJj80ob9ZAnBHdz5O1t

## Code and Resource used:

**Python Version**: 3.7

**Packages**: pandas, numpy, sklearn, matplotlib, seaborn.

**Generation of synthetic samples:** https://towardsdatascience.com/methods-for-dealing-with-imbalanced-data-5b761be45a18

## **1.  Exploratoy Data Analysis (EDA)**

*  Loading data
*  Statistics of the data frame
*  Data visualization
*  Data Cleaning
*  Fixing formats
## **2.  Feature Engineering**

*  Create new features (domain knowledge, interactions, grouping). A good resource to read: https://elitedatascience.com/feature-engineering-best-practices
*  Data transformations: Most of the features were skewed to the right. I used the log transformation.
*  Getting dummy variables for categorical features.
*  Split data into train and test
*  Outlier detection
## **3.  Modeling and Evaluation**

*  I implemented a Naive Bayes algorithm as baseline model. ROC-AUC Score: 60.49
*  After running the baseline model, I used robust models:Random Forest, Decision Tree, Gradient Boosting, AdaBoosting, and XGBoost. Best performance with Xgboost and Random Forest.
*  Hyperparameter tunig for best models.
*  Feature importance analysis.
*  Final model: Xgboost Classifier. ROC-AUC Score: 70.22
