# Breast Cancer Prediction

A short project using the **Breast Cancer Wisconsin dataset** to classify tumors as **malignant or benign**.  
Compared three supervised learning models: **Logistic Regression**, **Random Forest**, and **Gradient Boosting**.

---

### 📘 Overview
- **Goal:** Predict tumor type based on diagnostic features.  
- **Dataset:** Scikit-learn's Breast Cancer dataset (569 samples, 30 features).  
- **Libraries:** pandas, numpy, matplotlib, scikit-learn.  

---

### ⚙️ Workflow
1. Data loading, exploration, and preprocessing (scaling, splitting).  
2. Model training and comparison.  
3. Evaluation with **accuracy**, **confusion matrix**, and **ROC–AUC**.  

---

### 📊 Results
| Model | Accuracy | AUC |
|--------|-----------|-----|
| Logistic Regression | **97.15%** | **0.99** |
| Random Forest | 94.73% | 0.99 |
| Gradient Boosting | 93.64% | 0.97 |

**Conclusion:** Logistic Regression performed best — data is mostly linearly separable.

---
