# Parkinson’s Disease Prediction Using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)](https://scikit-learn.org/)

## 📌 Project Overview
This repository contains a supervised machine learning solution designed to detect and predict **Parkinson's Disease** risk patterns using clinical voice measurements. By utilizing a **Support Vector Machine (SVM)** classifier, this model analyzes acoustic features extracted from speech recordings of 195 individuals to accurately differentiate between healthy individuals and patients diagnosed with Parkinson's.

The goal of this project is to leverage non-invasive vocal biomarkers to assist clinical practitioners in early-stage screening and diagnosis.

---

## 🛠️ Key Features & Methodology

*   **Exploratory Data Analysis (EDA):** Investigated clinical vocal features (MDVP jitter, shimmer, fundamental frequency, etc.) to understand feature distributions and correlate physical voice degradation with disease progression.
*   **Data Cleansing & Feature Standardization:** Handled outlier variance and applied feature scaling (z-score normalization) to eliminate magnitude bias, ensuring high stability and optimal performance during SVM optimization.
*   **Predictive Modeling:** Built, trained, and tuned a **Support Vector Machine (SVM)** classification pipeline optimized for high-dimensional clinical datasets.
*   **Evaluation Metrics:** Assessed model robustness using critical performance indicators including Accuracy, Precision, Recall, and F1-Score to minimize diagnostic false negatives.

---

## 📂 Repository Structure

```directorytext
Parkinsons-Disease-Prediction/
│
├── Parkinson's_Disease_Prediction.ipynb  # Jupyter Notebook with complete end-to-end ML workflow
└── README.md                             # Comprehensive project documentation
