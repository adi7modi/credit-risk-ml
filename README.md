Credit Risk Assessment ML Project

This project builds a machine learning model to predict whether a borrower will default on a loan using behavioral, psychometric, and financial features. The dataset was synthetically generated to simulate underbanked populations in India.


Dataset

The dataset includes 100,000 records with the following features:

- Loan Amount, Monthly Income, Loan To Income Ratio, Psychometric Score, Purpose Of Loan, Education Level, Employment Status
- Digital behavior:  UPI Transaction Volume, Data Usage , Online Purchases
- Derived features like Digital Activity Score, Behavioral Risk Flag

 A 1000-row sample is included as `**\*\*sample\_credit\_risk\_data.csv\*\***`.

---

ML Pipeline

- Preprocessing with `LabelEncoder`
- Train/test split
- Model used: `RandomForestClassifier` (50 estimators, depth 10)

---

Results

- Accuracy: **63.85%**
- Precision (Default=1): **64%**
- Recall (Default=1): **70%**
- F1 Score (Default=1): **67%**

The model shows strong recall, meaning it is effective at detecting likely defaulters.



 Files
