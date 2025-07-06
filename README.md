<h1>Cyber Attack Detection using Machine Learning</h1>

This project demonstrates a complete machine learning pipeline to detect cyber attacks using a large-scale dataset of over 2.5 million records. It showcases the process of cleaning real-world data, preventing data leakage, handling mixed data types, and training a highly accurate classification model.

<h3>Project Overview</h3>
<i>Objective: Detect cyber attacks using tabular network data</i>

<i>Dataset: UNSW-NB15 (2.5M+ records, 139 features)</i>

Final Model: XGBClassifier with 99.95% accuracy

Challenge: Cleaning high-dimensional data with mixed types and missing values

Technologies Used
Python 3.10+

pandas

numpy

scikit-learn

xgboost

imbalanced-learn (SMOTE, etc.)

matplotlib, seaborn

Steps Covered
Data Cleaning

Removed columns with excessive null values

Handled mixed-type fields (e.g., strings with numeric values)

Missing Value Imputation

Custom logic for assigning consistent numeric placeholders

Preventing Data Leakage

Removed IPs, ports, and other identifiers (srcip, dstip, sport, dsport)

Feature Engineering

Label encoding for categorical features

Standard scaling for numerical columns

Model Training & Evaluation

Models tested: Logistic Regression, SVM, Decision Tree, XGBoost

Best results with XGBoost

Performance Metrics

Precision, Recall, F1-Score all near 100%

Only 59 false negatives and 23 false positives out of over 500,000 samples
