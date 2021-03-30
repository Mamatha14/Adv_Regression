# Adv_Regression
### Problem Statement:
- Predicting the Sale Price of the houses using Advanced Regression Models such as Ridge and Lasso.
- Whcih are the variables significant in predicting the house price and how well those variables describe the house price.
### Steps involved:
- Data Understanding
- Data Cleaning: Checking for missing values, highly skewed variables & outliers and treating them.
- Data Preparation: Dummy Variable Creation, Train-Test Split, Scaling
- Model Building:
  - Feature Selection using RFE
  - Using Cross Validation technique to build both Ridge and Lasso Models.
- Model Evaluation: Use R2 and MSE metrics.
### Conclusion:
- Optimal Score for both Ridge and Lasso is 0.0001.
- Results of Ridge:
  - The R2-Score for training data is 0.848 and testing is 0.839.
  - The MSE for training is 0.024 and testing is 0.026.
  - Top 5 Predictors:
    1. MSZoning_RL
    2. MSZoning_RH
    3. MSZoning_FV
    4. MSZoning_RM
    5. ExterCond_Fa
- Results of Lasso:
  - The R2-Score for training data is 0.8474 and testing is 0.8418. This imples that the model is not overfitting.
  - The MSE for training is 0.024 and testing is 0.026
  - Top 5 Predictors:
    1. MSZoning_RL
    2. MSZoning_RH
    3. MSZoning_FV
    4. MSZoning_RM
    5. BsmtQual_No Basement 
