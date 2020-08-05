# Customer Churn Prediction

### DATASET:

There are total 20 features:
state, account_length, area_code, phone_number, intl_plan, voice_mail_plan, number_vmail_messages, total_day_minutes, total_day_calls, total_day_charge, total_eve_minutes, total_eve_calls, total_eve_charge, total_night_minutes, total_night_calls, total_night_charge, total_intl_minutes, total_intl_calls, total_intl_charge, number_customer_service_calls, churned

### OBJECTIVE:

The objective of this project is to identify customers who are likely to stop using service in the future and analyze top factors that influce user retention. This is the binary classification  problem. The target of the dataset is to predict whether the new customer is going to "churn" or "not churn"

### PREPROCESSING:

Data clearning, feature understanding and feature processing were used first.

### MODEL TRAINING AND MODEL EVALUATION:

Three differetn classification regression models were used: KNN, logistic regression and random forest. hyperparameters were found by using grid search techniqies for different models.

Precission, recall and accuracy were used to evalaute these three different models.

Feature importance was also investigated at the end.
