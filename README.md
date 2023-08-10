# Credit Risk Analysis Report

## Overview
The purpose of this analysis is to evaluate the performance of a logistic regression model for credit risk assessment. The analysis involves training and testing the model on loan data, initially addressing class imbalance through random oversampling. The goal is to assess the model's ability to predict both healthy and high-risk loans, which can aid in making informed decisions about loan approvals.

## Results
- **Original Model (Imbalanced Data):**
  - Accuracy Score: 0.99
  - Precision Score (Class 0): 1.00
  - Precision Score (Class 1): 0.85
  - Recall Score (Class 0): 0.99
  - Recall Score (Class 1): 0.91

- **Resampled Model (Balanced Data):**
  - Accuracy Score: 0.99
  - Precision Score (Class 0): 1.00
  - Precision Score (Class 1): 0.84
  - Recall Score (Class 0): 0.99
  - Recall Score (Class 1): 0.99

## Summary
The logistic regression model showcased promising results in credit risk assessment, both with the original imbalanced data and after applying random oversampling to address class imbalance.

- In the original model, the accuracy was high at 0.99, indicating strong overall predictive capability. Precision for healthy loans (class 0) was perfect, while precision for high-risk loans (class 1) was 0.85. This suggests that the model excelled at correctly identifying healthy loans, but there was room for improvement in predicting high-risk loans. The recall for both classes was also good, demonstrating the model's ability to capture actual instances.

- After applying random oversampling to balance the data, the model's performance improved further. The accuracy, precision, and recall scores for class 1 (high-risk loans) saw notable enhancements. Precision decreased slightly to 0.84, indicating a trade-off between minimizing false positives and maximizing true positives. However, recall increased to 0.99, showcasing the model's effectiveness in capturing a higher proportion of actual high-risk loans.

Considering the business context, the resampled model's balanced accuracy and improved performance on high-risk loans make it a valuable tool for credit risk assessment. The trade-off between precision and recall can be fine-tuned based on the company's priorities. While the original model exhibited strong accuracy, the resampled model's improved recall for high-risk loans justifies its recommendation.

---

