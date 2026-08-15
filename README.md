# SmartCare-Ai-Risk-Prediction

> AI-powered disease risk classification system for SmartCare Hospital using ML, EDA, and Explainable AI (SHAP) — CCS3440 Artificial Intelligence coursework project.

---

## 📁 Project Structure

```
SmartCare-Ai-Risk-Prediction/
│
├── data/
│   ├── raw/                    # Original raw dataset
│   └── processed/              # Cleaned and engineered data (X_train.csv, etc.)
│
├── models/                     # Trained models and selection metadata
│   ├── logistic_regression.pkl
│   ├── random_forest.pkl
│   ├── xgboost.pkl
│   ├── decision_tree.pkl
│   └── final_model_selection.json
│
├── notebooks/
│   ├── 01_preprocessing_feature_engineering.ipynb  # Tasks 03 & 04
│   ├── 03_model_development.ipynb                  # Task 05
│   ├── 04_model_evaluation.ipynb                   # Task 06
│   ├── 05_explainable_ai_and_ethics.ipynb          # Tasks 07 & 08
│   └── 06_dashboard_deployment.ipynb               # Task 09 - Streamlit Dashboard
│
├── reports/
│   ├── evaluation_results.csv
│   └── figures/                # ROC curves, SHAP plots, Confusion Matrices, etc.
│
├── app/
│   └── app.py                  # Streamlit application
│
├── .gitignore
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation

```bash
git clone https://github.com/N3Edirisinghe/SmartCare-Ai-Risk-Prediction.git
cd SmartCare-Ai-Risk-Prediction
pip install -r requirements.txt
```

### Running the Streamlit App

```bash
streamlit run app/app.py
```

---

## 📓 Notebooks Overview

| Notebook | Description |
|---|---|
| `01_preprocessing_feature_engineering.ipynb` | Data cleaning, preprocessing, and feature engineering (Tasks 03 & 04) |
| `03_model_development.ipynb` | Training ML models: Logistic Regression, Random Forest, XGBoost, Decision Tree (Task 05) |
| `04_model_evaluation.ipynb` | Model evaluation using ROC-AUC, confusion matrix, classification report (Task 06) |
| `05_explainable_ai_and_ethics.ipynb` | SHAP explainability and AI ethics analysis (Tasks 07 & 08) |
| `06_dashboard_deployment.ipynb` | Streamlit dashboard deployment walkthrough (Task 09) |

---

## 🤖 Models Used

- Logistic Regression
- Random Forest
- XGBoost
- Decision Tree

---

## 📊 Evaluation Metrics

- Accuracy
- Precision / Recall / F1-Score
- ROC-AUC Score
- Confusion Matrix
- SHAP Feature Importance

---

## 🧠 Explainability

SHAP (SHapley Additive exPlanations) is used to provide transparent, interpretable predictions to medical staff.

---

## ⚖️ Ethics

This project includes an ethical analysis section covering:
- Bias and fairness in medical AI
- Transparency and accountability
- Patient data privacy

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**N3Edirisinghe**  
CCS3440 Artificial Intelligence — Coursework Project
