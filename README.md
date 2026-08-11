# 🫀 Heart Disease Prediction using Random Forest

> An interpretable machine learning project for predicting the presence
> of heart disease using the UCI Cleveland Heart Disease dataset.

## 📌 Project Overview

This project explores whether a Random Forest classifier can effectively
predict the presence of heart disease from clinical and demographic
patient attributes.

Rather than focusing only on prediction accuracy, the project also
investigates:

- Which features are most influential to the model
- Where the model makes incorrect predictions
- How correctly and incorrectly classified patients differ across
  important feature distributions
- How the model's predictions can be interpreted through classical
  machine learning analysis

The project was developed as a classical machine learning capstone
focused on ensemble learning and model interpretation.

---

## 🎯 Research Question

Can a Random Forest classifier trained on the UCI Cleveland Heart
Disease dataset achieve strong classification performance while
identifying the most influential patient attributes?

The accompanying research report investigates this question through
a literature review, experiment design, model evaluation, and error
analysis.

---

## 📊 Dataset

The project uses the **Cleveland Heart Disease dataset** from the
UCI Machine Learning Repository.

The dataset contains clinical and demographic attributes including:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Resting ECG
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Slope
- Number of major vessels
- Thalassemia

The original target contains multiple disease severity levels and is
converted into a binary classification problem:

| Target | Meaning                      |
| ------ | ---------------------------- |
| `0`    | No presence of heart disease |
| `1`    | Presence of heart disease    |

---

## 🔬 Machine Learning Workflow

The project follows a complete classical machine learning workflow:

```text
Raw Dataset
     │
     ▼
Data Inspection
     │
     ├── Missing-value analysis
     ├── Duplicate analysis
     └── Statistical exploration
     │
     ▼
Data Cleaning
     │
     ├── Replace missing values
     ├── Numeric conversion
     └── Median imputation
     │
     ▼
Target Transformation
     │
     ▼
Stratified Train/Test Split
     │
     ▼
Random Forest Classifier
     │
     ▼
Model Evaluation
     │
     ├── Accuracy
     ├── Precision
     ├── Recall
     ├── F1-score
     └── Confusion Matrix
     │
     ▼
Model Interpretation
     │
     ├── Feature Importance
     └── Error Analysis
```
