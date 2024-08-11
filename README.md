# credit-risk-classification
Financial details about loan applicants, such as loan amount, interest rate, borrower income, debt-to-income ratio, and number of accounts, are included in the dataset. The binary target variable indicates if a loan is healthy (0) or high-risk (1).

Overwiev of the Analysis:
Explain the purpose of this analysis.
The aim of this analysis is to develop a machine learning model capable of predicting loan applicants' credit risk. Through precise loan classification as high-risk or healthy, the model seeks to support financial institutions in lending decisions.

Results
Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
Accuracy Score: A 99% accuracy was attained by the model.
Class 0 (Healthy Loan): 1.00 Precision Score
Class 1 (Loan with High Risk): 0.85
Class 0 (Healthy Loan) Recall Score: 0.99
Class 1 (Loan with High Risk): 0.91

Summary
 Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
The logistic regression model performs remarkably well in detecting healthy loans(Class0), exhibiting a high degree of accuracy. The model's reliability in forecasting loans is demonstrated by the somewhat decreased but still great precision and recall for high-risk loans (Class 1) that might be more dangerous. Given the model's ability to balance memory and precision—particularly for the high-risk category—the corporation can consider using it. To better catch more subtle trends in loan data, more testing and fine-tuning on a variety of datasets may be necessary.
