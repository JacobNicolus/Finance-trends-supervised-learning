# Finance Trends 2020–2025 Supervised Learning Project

## Project Title

Predicting Investment Avenues Using Financial Behaviour Data

---

## Project Overview

This project applies supervised machine learning techniques to predict investment avenues using financial behaviour and demographic variables from the Finance Trends 2020–2025 dataset.

The project investigates:

* Baseline supervised learning performance
* Comparison of multiple machine learning models
* Effect of preprocessing strategies
* Feature importance and interpretability
* Sensitivity to evaluation metrics
* Robustness and generalization
* Final practical model recommendation

---

## Dataset Information

### Dataset Name

Finance Trends 2020–2025

### Dataset Source

https://www.kaggle.com/datasets/ayeshasiddiqa123/finance-trends-2020-2025

### Dataset Size

* Rows: 12,000
* Columns: 24

### Target Variable

Investment_Avenues

### Task Type

Classification

---

## Research Questions

### RQ1 — Baseline Performance

How effectively can baseline supervised learning models predict investment avenues?

### RQ2 — Model Comparison

Which supervised learning model achieves the best predictive performance?

### RQ3 — Effect of Preprocessing

How do preprocessing strategies affect model performance?

### RQ4 — Feature Importance

Which demographic and financial behaviour variables contribute most to prediction?

### RQ5 — Sensitivity to Evaluation Metrics

How does model ranking change under different evaluation metrics?

### RQ6 — Robustness and Generalization

How robust is the selected model under increasing label noise?

### RQ7 — Practical Usefulness and Final Recommendation

Which model provides the best balance between predictive performance, interpretability, robustness, and deployment suitability?

---

## Machine Learning Models Used

* Logistic Regression
* Decision Tree
* k-Nearest Neighbors (k-NN)
* Random Forest
* Gradient Boosting
* Support Vector Machine (SVM)

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Cross-Validation Performance

---

## Repository Structure

finance-trends-supervised-learning/

├── notebooks/
│   ├── RQ1_Baseline_Performance.ipynb
│   ├── RQ2_Model_Comparison.ipynb
│   ├── RQ3_Effect_of_Preprocessing.ipynb
│   ├── RQ4_Feature_Importance_and_Interpretability.ipynb
│   ├── RQ5_Sensitivity_to_Evaluation_Metrics.ipynb
│   ├── RQ6_Robustness_and_Generalization.ipynb
│   └── RQ7_Practical_Usefulness_and_Final_Recommendation.ipynb
│
├── figures/
├── tables/
├── proposal/
├── README.md
├── requirements.txt
└── dataset_link.txt

---

## How to Run the Project

### Step 1 — Download Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/ayeshasiddiqa123/finance-trends-2020-2025

---

### Step 2 — Open Kaggle Notebook

Upload the notebook files into Kaggle.

---

### Step 3 — Attach Dataset

Attach the Finance Trends 2020–2025 dataset.

---

### Step 4 — Run All Cells

Click:

Run → Run All

Each notebook automatically:

* trains machine learning models,
* generates tables,
* creates publication-ready figures,
* exports CSV tables,
* exports PDF figures.

---

## Generated Results

### Generated Tables

* Baseline model performance tables
* Model comparison tables
* Preprocessing impact tables
* Feature importance tables
* Metric sensitivity tables
* Robustness analysis tables
* Final decision matrix tables

### Generated Figures

* Grouped bar charts
* Heatmaps
* Feature importance plots
* Slope graphs
* Robustness line plots
* Radar charts

---

## Key Findings

* Ensemble models outperformed baseline models.
* Preprocessing improved predictive consistency.
* Certain financial behaviour variables strongly influenced predictions.
* Model performance decreased under increasing label noise.
* Random Forest provided the best balance between performance and robustness.

---

## Author

Jacob Nicolus Maggidi

---

## License

This project is for academic and educational purposes only.
