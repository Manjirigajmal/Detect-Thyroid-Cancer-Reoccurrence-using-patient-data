# Detect-Thyroid-Cancer-Reoccurrence-using-patient-data
Overview
This project focuses on predicting the likelihood of thyroid cancer recurrence in survivors using clinical and pathological data. Several machine learning models, including Random Forest, XGBoost, Support Vector Machine (SVM), Logistic Regression, and Gradient Boosting, are trained and evaluated to predict whether a thyroid cancer patient will relapse. The project leverages key performance metrics such as accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix results to assess model performance.

Problem Statement
Thyroid cancer survivors face a significant risk of recurrence, and accurately predicting this recurrence is crucial for early detection and timely intervention. With the potential to improve patient outcomes, this project applies machine learning techniques to predict the recurrence of thyroid cancer based on clinical and pathological features.

Key Features
Data Preprocessing: Categorical variables are encoded using one-hot encoding, and missing values are handled appropriately.
Model Selection: Five machine learning models are tested and evaluated:
Random Forest
XGBoost
Support Vector Machine (SVM)
Logistic Regression
Gradient Boosting

Evaluation Metrics: The models are evaluated using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix results to assess overall performance and effectiveness in predicting cancer recurrence.
ROC Curve Analysis: A key component of the analysis is the ROC curve and its AUC, providing insights into each model's discriminatory ability.
Dataset
The dataset used in this project includes clinical and pathological data for thyroid cancer patients, such as:
Age, gender, and medical history
Tumor characteristics (e.g., size, histology)
Treatment details (e.g., type of surgery, radiation therapy)
Post-treatment follow-up data (e.g., recurrence status)
The dataset is preprocessed and transformed to create a feature set suitable for machine learning algorithms.

Model Performance

Random Forest: The top-performing model, with an accuracy of 95.5%, precision of 92.6%, and an ROC-AUC of 0.99. It demonstrated an excellent trade-off between true positive and true negative rates, making it highly suitable for medical applications.

XGBoost: Close behind with an accuracy of 93.6%, precision of 86.2%, and ROC-AUC of 0.99. It is robust and reliable, performing well across all metrics.

SVM and Gradient Boosting: Both models performed well, with strong accuracy and precision but slightly lower AUC values than Random Forest and XGBoost.

Logistic Regression: While slightly lower in performance, it achieved a competitive accuracy of 96.4% and the highest precision of 96.2%, making it a good option for situations where model interpretability is a priority.

Conclusion

The project aims to demonstrate the application of machine learning to predict thyroid cancer recurrence, an important problem in medical diagnostics. Random Forest is identified as the best model for this task based on its strong predictive accuracy and reliable performance across key evaluation metrics. This work lays the foundation for improving patient care by facilitating early detection of cancer recurrence through predictive analytics.
