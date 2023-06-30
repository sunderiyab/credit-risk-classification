# credit-risk-classification

### Purpose of the analysis
The purpose of this analysis is to develop a machine learning model specifically logistic regression to predict the loan status as either a healthy loan (label 0) or a high risk loan (label 1).

### Analysis included: 
Data Preparation : The data is separated into labels (y) and features (X), and then oversampling is performed using the RandomOverSampler to address the class imbalance in the dataset.
Model Training: Logistic regression model is instantiated and trained using the oversampled training data.
Model Evaluation: The trained model is evaluated using various evaluation metrics to assess its performance in predicting both healthy loans and high-risk loans.


### The Results: 
Accuracy Score: The accuracy score of the logistic regression model is 0.99, indicating that it correctly predicts the loan status for approximately 99% of the samples.
Precision Scores:Precision for the 0 label (healthy loan) is 1.00, meaning that when the model predicts a loan as healthy, it is correct 100% of the time. Precision for the 1 label (high-risk loan) is 0.84, indicating that when the model predicts a loan as high-risk, it is correct 84% of the time.

### Summary of results:

Based on the overall analysis, I recommend using this logistic regression model for loan status prediction. The model exhibits high accuracy, precision, and recall scores for both healthy and high-risk loans. It is capable of correctly identifying the loan status in a majority of cases, which can aid the company in making informed decisions and mitigating risks associated with high-risk loans.
