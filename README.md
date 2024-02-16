# credit-risk-classification

Overview of the Analysis

The primary objective of this analysis was to assess the credit risk associated with both 'healthy' and 'high risk' loans. Machine learning models were developed to evaluate the creditworthiness of individuals based on their credit risk profiles. The analysis aimed to determine the overall accuracy and precision of these models.

Initially, the data was imported into a DataFrame from a provided CSV file. Subsequently, the dataset was divided into training and testing sets. A logistic regression model was then trained using the training data, followed by testing the model's performance on the test dataset. Predictions were generated based on the resulting model.

Results

Machine Learning Model 1:

Accuracy: 99%
Precision:
Healthy Loans: 100%
High Risk Loans: 87%
Recall:
Healthy Loans: 100%
High Risk Loans: 89%
Machine Learning Model 2:

Accuracy: 100%
Precision:
Healthy Loans: 100%
High Risk Loans: 87%
Recall:
Healthy Loans: 100%
High Risk Loans: 100%
Summary

The second model demonstrates marginally better predictive performance with a 100% accuracy rate. However, it is noteworthy that the precision for high-risk loans is only 87%, indicating potential inconsistencies in predicting loan defaults. Both models exhibit excellent accuracy in identifying healthy loans. However, their precision in identifying high-risk loans falls short of expectations, underscoring the challenges of accurately assessing creditworthiness, particularly for high-risk loans. This becomes particularly concerning given the inherent risk associated with such loans.
