# Enhancing Fairness and Interpretability in Credit Risk Assessment

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![XGBoost](https://img.shields.io/badge/Model-XGBoost-orange.svg)](https://xgboost.readthedocs.io/)
[![Fairness](https://img.shields.io/badge/Fairness-0.0001_Gap-green.svg)]()

This repository contains the complete *MIL (Machine Learning) Pipeline* for our research on credit risk. Our project bridges the gap between high-performance predictive modeling and ethical AI by integrating cost-sensitive learning with SHAP interpretability.

---

##  Project Highlights
- *Accuracy:* Achieved a peak predictive accuracy of *93.69%*.
- *Fairness:* Minimized the demographic fairness gap to an impressive *0.0001*.
- *Explainability:* Fully transparent decision-making process using *SHAP* values.
- *Robustness:* Optimized for highly imbalanced financial datasets (78/22 split).

---

##  Repository Structure

| Folder | Description |
| :--- | :--- |
|  *Data/* | Contains the benchmark credit_risk_dataset.csv. |
|  *Notebooks/* | The main .ipynb file with the full code pipeline. |
|  *Output/* | All generated visualizations (Confusion Matrices, SHAP plots, etc.). |
|  *IEEE_paper/* | The final technical research paper in PDF format. |

---

##  Dataset Information
The project utilizes the *Credit Risk Benchmark Dataset*.
- *Source:* [Kaggle - Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
- *Scale:* 32,581 records with 12 behavioral and demographic features.

---

## Machine Learning Models & Results

> We benchmarked multiple classifiers to identify the most robust model for credit risk prediction, with *XGBoost* demonstrating the highest performance after optimization.

| Model | Accuracy | Status |
| :--- | :---: | :--- |
| XGBoost Classifier | 93.69% | Selected Model |
| Random Forest | 92.45% | Benchmarked |
| Logistic Regression | 84.12% | Benchmarked |

---

##  Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/AbdulrahamnAlzahrani/Credit-Risk-Fairness-ML.git](https://github.com/AbdulrahamnAlzahrani/Credit-Risk-Fairness-ML.git)
2. Install dependencies:
   ```bash
   pip install xgboost shap scikit-learn seaborn matplotlib
3. Environment & Requirements:
   Python, XGBoost, SHAP, Scikit-learn, Pandas / NumPy, Seaborn / Matplotlib.
   
4. Run the notebook Notebooks/Credit_Risk_Pipeline.ipynb to reproduce the results.

---

##  Visual Results
Model Interpretability (SHAP)
The model's decisions are backed by logical financial indicators such as Loan-to-Income ratio and interest rates.

---

## Performance Matrix
Balanced Confusion Matrix showing our model's capability after applying cost-sensitive weights.

---

## Authors
* Abdulrahman Alzahrani - [Prince Sultan University]
* Osamah Dhuwayhi - [Prince Sultan University]

<p align="center">
Copyright 2026 | Credit Risk Fairness Study
</p>
