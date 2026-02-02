
# Heart Disease Prediction | Machine Learning Project

## 🚀 Overview

This project demonstrates an **end-to-end, industry-oriented machine learning workflow** A machine-learning–based decision-support system for early heart disease risk screening, designed to assist clinical prioritization.
It focuses on **real-world ML practices**: data analysis, model reliability, interpretability, and deployment readiness.

> Built as a **decision-support system**, not just a model.

---

## 🔍 Problem Statement

Heart disease is a leading global health risk. Early detection is critical.
The goal is to **accurately identify patients at risk** while minimizing missed disease cases (false negatives).

---

## 🧠 Solution Approach

* Performed **extensive exploratory data analysis (EDA)** to understand feature behavior
* Engineered and encoded mixed medical features (categorical + continuous)
* Built a **Random Forest classifier** optimized for:

  * Non-linear relationships
  * Medical safety (high recall for disease)
  * Robust generalization
* Evaluated using **industry-standard metrics**

---

## 📊 Model Performance (Final)

| Metric                  | Score     |
| ----------------------- | --------- |
| **Accuracy**            | **87%**   |
| **ROC-AUC**             | **0.846** |
| **Recall (Disease)**    | **90%**   |
| **Precision (Disease)** | **92%**   |

### Confusion Matrix

```
[[262  68]
 [ 89 786]]
```

✅ Strong disease detection
✅ Low false negatives (medical priority)
⚠️ Some false positives (acceptable for screening use-cases)

---

## 📈 Key Insights from EDA

* **Strong predictors:** `oldpeak`, `thalach`, `cp`, `ca`, `thal`, `slope`
* **Moderate predictors:** `age`, `chol`, `trestbps`
* **Weak predictors:** `fbs`, `restecg`

EDA validated **why Random Forest performs well** on this dataset.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, seaborn, matplotlib
* **ML:** scikit-learn
* **Model:** Random Forest Classifier

---

## 🏗️ Project Structure

```
├── data/
│   └── heart.csv
├── notebooks/
│   └── heart_disease_analysis.ipynb
├── model/
│   └── random_forest_model.joblib
├── README.md
```

---

## 🏥 Real-World Relevance

* Designed for **clinical risk screening**
* Prioritizes recall for disease detection
* Suitable as a **decision-support tool**, not autonomous diagnosis
* Ready for integration with APIs or dashboards

---

## 🚧 Future Improvements

* Threshold tuning to reduce false negatives further
* Model explainability with SHAP
* Deployment using FastAPI / Streamlit
* Comparison with XGBoost / LightGBM

---


