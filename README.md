Thyroid Cancer Prediction Using Data Mining Techniques
1. Abstract
This project focuses on predicting thyroid cancer using patient medical data. We investigated the feasibility of accurately predicting cancer types using machine learning techniques. Random Forest and Gradient Boosting Classifiers emerged as the top-performing model. The findings highlight the significance of specific features such as Pathology, Tumor Stage, Gender, and Age in predicting thyroid cancer. This project provides valuable insights that could aid healthcare professionals in early diagnosis.
2. Introduction
Thyroid cancer is a prevalent endocrine malignancy, especially among females. Early diagnosis can significantly improve patient outcomes. Machine learning techniques can analyze complex medical data and provide accurate predictions, helping to overcome traditional diagnostic challenges.
3. Objective
- Predict thyroid cancer using patient medical data.
- Identify the most influential features for prediction.
- Compare various machine learning models for accuracy and reliability.
4. Dataset Description
The dataset includes 383 patient records with features such as age, gender, smoking history, radiotherapy history, tumor stage, risk, and pathology (cancer type). The target variable is pathology, which encompasses different types of thyroid cancer, including papillary, follicular, micropapillary, and Hurthel cells.
5. Exploratory Data Analysis (EDA)
Most patients are female. Most diagnoses occur at early tumor stages (T1a) and Stage I. Patients primarily fall into low or intermediate-risk categories. The age distribution typically centers on middle age, showing no notable outliers. Unifocal tumors are more common than multifocal tumors. There are rare instances of metastasis and recurrence.
6. Data Preprocessing
Data preprocessing included label encoding for categorical features, verifying for missing values, and dividing the dataset into training and testing sets. Numeric features were utilized directly, while categorical features were encoded as needed.
7. Model Building
The models utilized in this project included the Logistic Regression, decision Tree Classifier, Random Forest Classifier, Support Vector Machine (SVM), XGBoost Classifier, Neural Network, and gradient Boosting classifier.  The Random Forest and Gradient Boosting exhibited the highest accuracy and robustness.
8. Model Evaluation
The performance of the models was evaluated using:
- Accuracy
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix
9. Result Summary
- The Random Forest and Gradient Boosting model achieved the highest accuracy.
- Pathology, Tumor Stage, Gender, and Age were significant predictors.
10. Conclusion
This project successfully demonstrated the feasibility of predicting thyroid cancer types using patient data. The Random Forest model and Gradient Boosting proved to be the most reliable. Key features influencing predictions included pathology, tumor stage, gender, and age. These insights could aid healthcare professionals in early diagnosis and treatment planning.
11. Recommendation & Future Work
- Gather data from benign cases for binary classification.
- Incorporate hormonal test data such as TSH, T3, and FT4 for more thorough analysis.
- Implement hyperparameter tuning to enhance model performance.
- Investigate deep learning models for larger datasets.
12. References
- Dataset Source:  UCI
- Scikit-learn Documentation
- Research Articles on Thyroid Cancer Prediction
