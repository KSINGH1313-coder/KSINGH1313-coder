# 🏦 Loan Approval Prediction System

A machine learning project that predicts whether a loan should be approved or rejected based on applicant financial data using **XGBoost** and **Random Forest** classifiers.

---

## 📊 Dataset

The dataset includes features like:

- `income_annum`: Annual income of the applicant
- `loan_amount`: Requested loan amount
- `loan_term`: Loan tenure in months
- `cibil_score`: Credit score (300-900)
- `residential_assets_value`, `commercial_assets_value`, `luxury_assets_value`, `bank_asset_value`: Asset values
- `loan_status`: Target variable (1 = Approved, 0 = Rejected)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn (optional for EDA)
- Flask (optional for deployment)

---

## 🧠 ML Models

- Models Trained:
  - ✅ XGBoost Classifier
  - ✅ Random Forest Classifier
- Hyperparameter tuning done using `GridSearchCV`
- Evaluation Metrics:
  - Accuracy, Precision, Recall, Confusion Matrix

---

## 🚀 How to Run

### 🛠️ Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/KSINGH1313-coder/loan-approval-prediction.git
   cd loan-approval-prediction
