# 🚀 Graph-Based Fraud Detection using Machine Learning

## 📌 Overview
This project enhances traditional fraud detection by incorporating **graph-based features** from financial transaction networks.

## 🎯 Key Idea
Instead of treating transactions independently, we model them as a **network of interactions between accounts**, capturing hidden fraud patterns.

---

## 🧠 Models Used
- XGBoost (baseline)
- XGBoost + Graph Features

---

## 🔗 Graph Features
- Node Degree
- PageRank
- Transaction Frequency
- Transaction Velocity

---

## 📊 Results
Graph-based features improved fraud detection performance by capturing relationships between accounts.

| Model | F1 Score |
|------|--------|
| Baseline | ~0.64 |
| Graph Model | **~0.70+** |

---

## 🔍 Explainable AI (SHAP)

SHAP analysis shows:
- Transaction amount is a key driver
- Graph features (PageRank, degree) significantly impact fraud prediction

![SHAP](images/shap_summary.png)

---

## 📈 PR Curve

![PR Curve](images/pr_curve.png)

---

## 📄 Research Paper
👉 [Zenodo Link]

---

## 🛠️ Tech Stack
Python, XGBoost, NetworkX, SHAP, Scikit-learn

---

## 👤 Author
Imtiaz Islam  
MS Computer Science – CUNY Baruch
