# 🚗 Prestacar: Default Prediction & Model Validation

## 🚀 Project Overview

This repository focuses on developing a robust classification model to predict **loan default risk** for "Prestacar," an automotive financing company. The primary goal is not just to build a predictive model, but to implement a rigorous **validation and evaluation framework** to ensure the model's reliability in a real-world financial environment.

Using the `prestacar.csv` dataset, we address the common pitfalls of machine learning, such as data leakage, overfitting, and class imbalance.

---

## 🎯 Key Learning Objectives

* **Validation Rigor:** Moving beyond simple train/test splits to complex validation strategies.
* **Performance Metrics:** Deep dive into Precision, Recall, F1-Score, and AUC-ROC to evaluate financial risk.
* **Data Integrity:** Implementing data balancing techniques (Oversampling/Undersampling) without introducing bias.
* **Process Automation:** Using Scikit-Learn **Pipelines** to ensure a clean, reproducible workflow from preprocessing to prediction.

---

## 📂 Repository Structure

* `Clasificacion_validacion_y_metricas.ipynb`: The primary development notebook containing the analysis, model training, and evaluation.
* `data/`: Directory intended for local storage of the `prestacar.csv` (or direct link via URL).
* `README.md`: Project documentation and setup guide.

---

## 💻 Environment & Setup

The project is designed to run seamlessly on **Google Colaboratory**, leveraging its pre-installed data science ecosystem.

1. **Direct Access:** Open the `.ipynb` file in Google Colab.
2. **Dataset:** The model fetches data directly from:
> [Alura Cursos Dataset: prestacar.csv](https://github.com/alura-es-cursos/2162-clasificacion-validacion-de-modelos-y-metricas/blob/main/prestacar.csv)


3. **Core Libraries:**
* `scikit-learn` (Model selection, validation, and metrics)
* `pandas` (Data manipulation)
* `numpy` (Numerical operations)
* `matplotlib/seaborn` (Visualization)



---

## 🛠 Methodology Highlights

To ensure the model is "bank-grade," we implement the following:

### 1. Validation Strategies

* **Hold-out Method:** Initial baseline testing.
* **K-Fold Cross-Validation:** Ensuring results are consistent across different data subsets.
* **Stratified Shuffled Split:** Maintaining the proportion of "defaulters" vs. "payers" across all folds.

### 2. Handling Class Imbalance

Default events are typically rarer than successful payments. We explore:

* **Undersampling:** Reducing the majority class.
* **Oversampling (SMOTE):** Creating synthetic instances of the minority class.

### 3. ML Pipelines

To prevent **Data Leakage**, all transformations (scaling, balancing) are wrapped inside a `Pipeline`. This ensures that the validation sets remain "unseen" during the training phase.

---

## 📈 Analysis Workflow

1. **Exploratory Data Analysis (EDA):** Understanding the features and target distribution.
2. **Baseline Modeling:** Training a simple classifier (e.g., Decision Tree or Logistic Regression).
3. **Model Validation:** Implementing Cross-Validation to get a realistic estimate of error.
4. **Metric Optimization:** Evaluating the trade-off between **Precision** (avoiding false alarms) and **Recall** (catching all potential defaults).
5. **Final Refinement:** Hyperparameter tuning and final model report.

---
