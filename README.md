# Banking Churn Prediction

This project focuses on predicting customer churn in a banking context using machine learning techniques. The dataset used for this analysis contains various features such as credit score, geography, gender, age, tenure, balance, number of products, whether the customer has a credit card, whether they are an active member, estimated salary, and the churn status (Exited).

## Table of Contents

- [Data Sources](#data-sources)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion](#conclusion)

## Data Sources

The dataset used in this project contains the following columns:

1. RowNumber: The row number.
2. CustomerId: Unique identifier for the customer.
3. Surname: Customer's surname.
4. CreditScore: Customer's credit score.
5. Geography: Customer's country of residence.
6. Gender: Customer's gender.
7. Age: Customer's age.
8. Tenure: Number of years the customer has been with the bank.
9. Balance: Customer's account balance.
10. NumOfProducts: Number of bank products the customer uses.
11. HasCrCard: Whether the customer has a credit card (1 = Yes, 0 = No).
12. IsActiveMember: Whether the customer is an active member (1 = Yes, 0 = No).
13. EstimatedSalary: Estimated salary of the customer.
14. Exited: Whether the customer exited the bank (1 = Yes, 0 = No).

## Modeling

Different machine learning models were trained on the dataset to predict customer churn. Among all models, Random Forest yielded the best performance.
The different models are:

- Logistic Regression
- Support Vector Machine
- KNN
- Decision Tree
- Random Forest
- Gradient Boosting Machine

## Evaluation Metrics

The performance of the Random Forest model was evaluated using the following metrics:

- Accuracy: The proportion of correctly classified instances.
- Precision: The proportion of true positive predictions among all positive predictions.
- Recall: The proportion of true positive predictions among all actual positive instances.
- F1 Score: The harmonic mean of precision and recall.

## Conclusion

The Random Forest model outperformed other models in predicting customer churn based on the provided dataset. Further improvements and optimizations can be explored to enhance the model's performance.
