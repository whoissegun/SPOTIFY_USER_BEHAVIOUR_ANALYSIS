# SPOTIFY_USER_BEHAVIOUR_ANALYSIS


This repository provides an in-depth analysis of user behavior data on Spotify, powered by Python's powerful data analysis libraries, pandas and matplotlib. The dataset used in the study is accessible via this link: https://www.kaggle.com/datasets/meeraajayakumar/spotify-user-behavior-dataset

The project's central focus is to generate data-driven insights from the provided dataset and to use these insights to build predictive machine learning models. The models developed aim to forecast user behavior related to Spotify's premium plan subscription.

1) PremiumPlanSubscriptionAmountPredictorV1: This machine learning model was designed to predict the amount a user would be willing to pay for a premium plan. The model performed impressively, achieving an accuracy of 91%. Below is the classification report showcasing its performance across different classes:

   **Classification Report for PremiumPlanSubscriptionAmountPredictorV1:**

|   | precision | recall | f1-score | support |
|---|-----------|--------|----------|---------|
| 0 | 0.96      | 0.98   | 0.97     | 56      |
| 1 | 0.92      | 0.92   | 0.92     | 24      |
| 2 | 0.98      | 0.74   | 0.84     | 68      |
| 3 | 0.91      | 0.94   | 0.92     | 133     |
| 4 | 0.85      | 0.99   | 0.91     | 67      |

|   |   |
|---|---|
| accuracy   | 0.91 348 |
| macro avg  | 0.92 0.91 0.91 348 |
| weighted avg | 0.92 0.91 0.91 348 |

**Accuracy: 0.9138**



2) PremiumPlanSubscriptionPredictorV3: The second model aims to predict whether users would be interested in subscribing to or maintaining their existing Spotify premium plan. This model achieved a decent accuracy score of 75%. Below is its detailed performance as per the classification report:

   Classification Report for PremiumPlanSubscriptionPredictorV3:
           precision    recall  f1-score   support
      0.0       0.76      0.88      0.82       108
      1.0       0.72      0.53      0.61        64
accuracy                           0.75       172
macro avg       0.74      0.71      0.71       172
weighted avg       0.75      0.75      0.74       172
Accuracy: 0.75


These models provide an opportunity to leverage machine learning to gain valuable insights and make informed predictions about user behaviors, which could be instrumental in strategic decision-making processes, specifically in enhancing subscription services and user experience.
