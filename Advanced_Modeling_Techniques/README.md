# Advanced Linear Regression Module

Welcome to the **Advanced Modeling Techniques** repository. This project focuses on implementing robust linear regression workflows, comparing statistical and machine learning approaches to data analysis.

---

## 🚀 Project Overview

This module explores the end-to-end process of building predictive models, from initial data transformations to the deep interpretation of coefficients. The goal is to move beyond basic fitting and master the nuances of model diagnostics and advanced estimation.

### Key Learning Objectives:

* **Data Preprocessing:** Applying transformations before model training to meet statistical assumptions.
* **Dual-Library Implementation:** Building models using both `Statsmodels` (for statistical depth) and `Sklearn` (for predictive efficiency).
* **Advanced Modeling:** Implementation of sophisticated regression techniques.
* **In-depth Interpretation:** Analyzing estimated coefficients to understand feature impact.
* **Visual Diagnostics:** Utilizing graphical analysis to validate model results and residuals.

---

## 📁 Repository Structure

| File | Description |
| --- | --- |
| `Regresion_lineal.ipynb` | The main execution notebook containing all experiments and analysis. |
| `dataset.csv` | The primary dataset used for training, testing, and validation. |

---

## 💻 Environment & Setup

This project is optimized for **Google Colab**.

To run this project:

1. Upload `Regresion_lineal.ipynb` to your Google Drive.
2. Open the notebook with Google Colab.
3. Ensure `dataset.csv` is uploaded to the Colab session storage or linked via Drive.
4. Run the cells sequentially to observe the transformations and model outputs.

---

## 📊 Methodology Highlights

> **Note:** We prioritize the "why" behind the numbers. While `Sklearn` provides the `predict()` functionality, `Statsmodels` is utilized to extract p-values and confidence intervals for a more rigorous interpretation.

### Analysis Workflow:

1. **Transformations:** Scaling and encoding variables to optimize model convergence.
2. **Estimation:** Running the regression engines.
3. **Point Predictions:** Generating specific numerical forecasts.
4. **Graphical Analysis:** Plotting residuals, homoscedasticity checks, and actual vs. predicted values.

---
