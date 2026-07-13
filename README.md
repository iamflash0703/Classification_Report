# 🩺 Breast Cancer Classification

Built and compared two classification models — Logistic Regression and Decision Tree — to predict whether a breast tumor is malignant or benign, based on cell measurements. 

## 📌 Overview
This project covers the full classification workflow — data preparation, feature scaling, model training, evaluation, and feature importance analysis — using the Breast Cancer Wisconsin dataset (built into Scikit-learn).

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🔍 Steps Followed
1. **Data Preparation** — Loaded 569 samples with 30 numeric features directly from Scikit-learn.
2. **Data Splitting** — 80-20 train-test split using stratified sampling to preserve class balance.
3. **Feature Scaling** — Standardized features using `StandardScaler` (required for Logistic Regression).
4. **Model Building** — Trained both `LogisticRegression` and `DecisionTreeClassifier`.
5. **Model Evaluation** — Compared Accuracy, Precision, Recall, and F1-Score.
6. **Feature Importance** — Identified which cell measurements matter most for prediction.

## 📊 Results

| Metric    | Logistic Regression | Decision Tree |
|-----------|---------------------|----------------|
| Accuracy  | 98.25%               | 93.86%         |
| Precision | 98.61%               | 95.77%         |
| Recall    | 98.61%               | 94.44%         |
| F1-Score  | 98.61%               | 95.10%         |

**Key takeaway:** In medical diagnosis, Recall matters most — minimizing false negatives (missed malignant cases) is critical. Logistic Regression achieved 98.61% recall.

## 📁 Files
- `classification_breast_cancer.py` — full commented done in py file
- `*.png` — confusion matrix, model comparison, feature importance plots

