# credit-risk-classification

Analysis Report

Overview
This report presents an analysis of credit risk assessment using logistic regression models applied to historical lending data from a peer-to-peer lending platform. Two models were developed: one using the original imbalanced dataset and another employing oversampling to address class imbalance. The objective is to enhance the identification of high-risk loans while maintaining robust overall predictive performance.

Results:
  •	Model Trained in Original Data:
    o	Balanced Accuracy Score: 0.968
    o	Precision: 
      	Healthy Loans (0): Approximately 1.00
      	High-Risk Loans (1): Approximately 0.84
    o	Recall: 
      	Healthy Loans (0): Approximately 0.99
      	High-Risk Loans (1): Approximately 0.94
  •	Model Trained on Oversampled Data:
    o	Balanced Accuracy Score: 0.994
    o	Precision: 
      	Healthy Loans (0): Approximately 1.00
      	High-Risk Loans (1): Approximately 0.84
    o	Recall: 
      	Healthy Loans (0): Approximately 0.99
      	High-Risk Loans (1): Approximately 0.99

Summary
The logistic regression model trained on the original dataset demonstrated strong performance in predicting healthy loans, but its ability to detect high-risk loans was compromised by class imbalance. The oversampled model exhibits improved detection of high-risk loans, as evidenced by the enhanced recall and balanced accuracy. As a result, the model built on oversampled data is recommended for credit risk assessment, as it provides a more balanced and reliable prediction across both classes, thereby supporting more informed lending decisions.
