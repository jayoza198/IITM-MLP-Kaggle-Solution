# MLP IITM Kaggle Solution - E-commerce Customer Behavior Analysis

## Problem Statement

Assume that you are working in a consultancy company and one of your clients is running an e-commerce company. They are interested in understanding the customer behavior regarding shopping. They have already collected the users’ session data for a year. Each row belongs to a different user. The "Made_purchase" is an indicator of whether the user has made a purchase or not during that year. Your client is also interested in predicting that column using other attributes of the users. The client also informs you that the data is collected by non-experts. So, it might have some percentage of error in some columns.

## Solution Approach

To address the problem, I used the following techniques and libraries:

- **Sklearn**: Sklearn is a powerful machine learning library in Python that provides various algorithms and tools for data analysis and modeling.

- **Ensemble Techniques**: I employed ensemble techniques such as Random Forest, XGBoost, and AdaBoost. Ensemble methods combine multiple models to improve prediction accuracy.

- **Hyperparameter Tuning**: I performed hyperparameter tuning to find the optimal configuration for each ensemble model. This process involves systematically searching different combinations of hyperparameters to identify the best performing model.

- **Voting Classifier**: I used a Voting Classifier, which combines the predictions from multiple individual models, to obtain the best classification result. The voting classifier aggregates the predictions from each model and selects the most common prediction as the final output.

**Accuracy** - 0.6599051633298209
