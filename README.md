# Treue_Technologies_BankCustomerChurn
# Bank Customer Churn Prediction

![Bank Customer Churn](https://github.com/AnujPathekar/Images/blob/main/BankCustomerChurnPrediction.jpg)


### Objective - The task is to train a machine learning model to predict whether a bank customer will churn (leave the bank) or not based on various customer attributes and banking behavior. The goal is to create a model that can accurately identify customers who are likely to churn, enabling proactive retention strategies.

## Dataset Description

This dataset contains 10000 rows and × 14 different columns.

### Target Column

The target column in this dataset is **Exited**.

[Dataset Download Link](https://github.com/AnujPathekar/Treue_Technologies_BankCustomerChurn/blob/main/Churn_Modelling.csv)
### Data Dictionary

| Variable          | Definition                                      |
|-------------------|-------------------------------------------------|
| RowNumber         | Unique Row Number                               |
| CustomerId        | Unique Customer Id                              |
| Surname           | Surname of a customer                           |
| CreditScore       | Credit Score of each Customer                   |
| Geography         | Geographical Location of Customers              |
| City_Category     | Category of the City (A, B, C)                  |
| Gender            | Sex of Customers                                |
| Age               | Age of Each Customer                            |
| Tenure            | Number of years                                 |
| Balance           | Current Balance of Customers                    |
| NumOfProducts     | Number of Products                              |
| HasCrCard         | If a customer has a credit card or not          |
| IsActiveMember    | If a customer is active or not                   |
| EstimatedSalary   | Estimated Salary of each Customer               |
| Exited            | Customer left the bank or Not (Target Variable) |

### Work Pipeline

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis
4. Data Modelling (Random Forest, Decision Tree, Logistic Regression)
5. Visualising
6. Conclusion

### Result

| Classifier                  | Accuracy Score | AUC   |
|---------------------------- | ---------------|-------|
| Logistic Regression         | 85.47%         | 0.70  |
| Random Forest Classifier    | 84.50%         | 0.62  |
| Decision Tree Classifier    | 80.47%         | 0.50  |

### Classifier Performance Analysis

The table presents the performance metrics of three different classifiers: Logistic Regression, Random Forest Classifier, and Decision Tree Classifier. These classifiers were evaluated based on their accuracy scores and AUC (Area Under the Curve) values.

- **Logistic Regression:** This classifier achieved the highest accuracy score among the three, with an accuracy of approximately 85.47%. Additionally, it exhibited a relatively high AUC of 0.70, indicating good discrimination ability in distinguishing between classes. This suggests that Logistic Regression is a strong candidate for this classification task.

- **Random Forest Classifier:** The Random Forest Classifier performed well with an accuracy score of around 84.50%. While its accuracy is slightly lower than Logistic Regression, it still indicates a strong predictive performance. The AUC value of 0.62 suggests that it has a good ability to classify instances correctly.

- **Decision Tree Classifier:** The Decision Tree Classifier achieved an accuracy score of approximately 80.47%, which is slightly lower than the other two classifiers. Its AUC value of 0.50 indicates that it performs at a chance level in distinguishing between classes. This suggests that the Decision Tree Classifier may require further tuning or might not be the most suitable choice for this specific task.

In conclusion, Logistic Regression appears to be the best-performing classifier for this classification problem, as it achieved the highest accuracy and AUC values. However, the choice of the classifier should also consider other factors such as interpretability, computational complexity, and specific business requirements.

