
---

# 📈 Customer Lifetime Value (CLV) Prediction

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge\&logo=Python\&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge\&logo=pandas\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB6C39?style=for-the-badge\&logo=xgboost\&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge\&logo=plotly\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge\&logo=TensorFlow\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge\&logo=PyTorch\&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge\&logo=Microsoft-Excel\&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-0078d7.svg?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge\&logo=markdown\&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge\&logo=github\&logoColor=white)

---

## 🧩 **Overview**

Customer Lifetime Value (CLV) is a key metric used to estimate the total economic value a customer contributes over the duration of their relationship with a business. In modern competitive environments—where customer acquisition costs are high—accurately predicting customer value helps organizations drive **better marketing decisions, retention strategies, and resource allocation**.

This project builds a complete modeling pipeline for CLV, including feature engineering, customer segmentation, and future value prediction.

---

## 🎯 **Project Objectives**

The primary goal of this project is to:

✔ Estimate the lifetime value of customers using historical transactional data
✔ Identify high-value and at-risk customer segments
✔ Support data-driven marketing strategies & retention programs
✔ Forecast expected revenue contribution using machine learning

---

## 🧠 **Problem Statement**

Given historical purchasing behavior, the task is to:

> **Predict the Customer Lifetime Value (CLV)** for each customer over a defined future horizon.

Challenges addressed include:

* irregular purchase frequency
* customer churn variability
* limited or incomplete purchasing patterns
* segmentation for tailored strategies

---

## 📊 **Dataset Description**

Dataset includes:

* Transaction records
* Dates & timestamps
* Customer identifiers
* Quantity & pricing
* Country & geographic info

These are used to compute:

* **R**ecency — time since last purchase
* **F**requency — number of purchases
* **M**onetary — total revenue contribution

---

## 🧮 **Modeling Approach**

This project follows a two-stage pipeline:

### **1. RFM Segmentation**

Using clustering methods (K-Means) to create:

* Low-value customers
* Mid-value customers
* High-value customers

Based on recency, frequency, and revenue behavior.

### **2. Machine Learning Prediction**

Supervised model (XGBoost) is trained to predict future CLV tiers and expected monetary value.

Metrics evaluated include:

* Classification accuracy
* MAE / RMSE (for value estimation)
* Cluster precision / recall

---

## 📈 **Metrics & Evaluation**

Multiple performance criteria are used:

| Metric               | Purpose                              |
| -------------------- | ------------------------------------ |
| **RMSE**             | Measures prediction error magnitude  |
| **MAE**              | Robust measure of absolute deviation |
| **R² Score**         | Measures explanatory power           |
| **Precision/Recall** | For tier-based value segmentation    |

---

## 📂 **Project Structure**

```
├── LICENSE
├── README.md            <- Project documentation
├── notebooks            <- Analysis notebooks & CLV modeling pipeline
│   └── clv.py
│   └── clv.ipynb
├── reports
│   └── Report.pdf       <- Final analytical report
├── src
│   ├── data             <- Raw & processed datasets
│   └── model            <- ML modeling modules & utilities
```

---

## 🚀 **Applications**

This CLV model enables:

✔ Marketing campaign optimization
✔ Targeted retention strategies
✔ Personalized offers & loyalty incentives
✔ ROI-based customer acquisition planning
✔ Resource allocation for lifecycle management

---

## 📦 **Future Enhancements**

To further improve modeling accuracy:

* Integrate churn probability estimation
* Introduce survival models (e.g., Pareto/NBD, BG/NBD)
* Leverage deep learning for sequence modeling
* Include demographic & behavioral data
* Compute probabilistic **Predicted LTV (PLTV)** at scale

---

## 📎 **Deliverables**

This repository provides:

✔ Reproducible modeling pipeline
✔ Analytical reporting (PDF)
✔ Source code for ML models
✔ Visualization & segmentation insights
✔ Clean project documentation

---