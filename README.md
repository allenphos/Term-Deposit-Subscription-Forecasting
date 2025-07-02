# Forecasting Term Deposit Subscriptions

This repository contains code and results from a machine learning project aimed at predicting the likelihood of clients subscribing to term deposit accounts.

## Problem Description:

Banks are interested in forecasting the probability that potential clients will open a term deposit. This helps them optimize marketing strategies, personalize offers, and improve customer engagement efficiency.

As part of this project, a machine learning model was developed to predict the likelihood of a term deposit subscription based on client demographic data, interaction history with the bank, and socio-economic indicators.

## Dataset:

The model was trained and tested using the "Bank Marketing" dataset from the UCI Machine Learning Repository. This dataset includes information from previous bank marketing campaigns and features such as age, occupation, marital status, education level, credit history, and more.

## Methods:

Several machine learning methods were employed in model development, including:

- Logistic Regression  
- K-Nearest Neighbors  
- Decision Trees  
- XGBoost  

The best results were achieved using the XGBoost model.
![image](https://github.com/user-attachments/assets/244dbeb8-a1c0-44b4-b03e-c383ce682b0e)
## Results:

The developed model achieved an AUROC score of **0.94** on the validation set, indicating a high level of accuracy in predicting term deposit subscriptions.

## Conclusions:

The study shows that machine learning can be an effective tool for predicting client behavior in banking. The model has potential to improve the effectiveness of marketing campaigns and increase bank profitability.

**Key insights:**

- **Contact duration:** The most significant factor, directly correlated with campaign success.  
- **Timing:** Months like April, March, and November show increased likelihood of subscriptions.  
- **Socio-economic context:** The composite `economic_health_index` and individual socio-economic features strongly influence client decisions.  
- **Demographics:** Clients aged 30–50 are more likely to subscribe.  
- **Contact channel:** Mobile phone contact increases the likelihood of success.  
- **Financial condition:** Clients without debt and with consumer credit are more likely to subscribe.  
- **Past campaigns:** Results from previous campaigns (`poutcome_codes`) are important predictors.

## Next Steps:

- Further error analysis to uncover new patterns and improvement areas.  
- Add polynomial features.  
- Tune classification thresholds.  
- Class balancing: Apply methods to address class imbalance, particularly for the "success" class.  
- Feature Engineering and Selection: Explore and add new features to improve model informativeness.  
- Hyperparameter Optimization: Tune XGBoost hyperparameters to boost accuracy.  
- Regularization: Apply regularization techniques to prevent overfitting.

