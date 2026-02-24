# 🏠 House Price Prediction using Linear Regression

In this course, we aim to **estimate the selling price of houses** by analyzing the different characteristics that influence property pricing.

To achieve this objective, we use **Linear Regression** as the primary modeling methodology.

The project focuses on understanding how housing features impact sale prices and how regression techniques can be applied to build reliable predictive models.

---

## 📌 Project Environment

The project is developed using **Google Colab**.

Main notebook:

```
precios_de_inmuebles_regresion_lineal.ipynb
```

The notebook contains:

* Exploratory Data Analysis (EDA)
* Linear regression modeling
* Model interpretation
* Performance evaluation
* Predictions

---

## 📊 Dataset

This project is based on the **House Price dataset from Kaggle**, with some transformations applied to the original data to ensure better learning and modeling practices.

Dataset file:

```
precios_casas.csv
```

The dataset has been preprocessed and adapted for educational purposes.

---

## 📁 Available Features for Analysis

Below are the variables included in the dataset:

### 🏗 Structural Features

* **`area_primer_piso`**
  First floor area of the property, measured in square meters.

* **`existe_segundo_piso`**
  Binary variable indicating whether the property has a second floor:

  * `1` → Yes
  * `0` → No

* **`area_segundo_piso`**
  Total area of the second floor in square meters (if applicable).

* **`cantidad_baños`**
  Total number of bathrooms in the property.

* **`capacidad_coches_garaje`**
  Garage capacity (maximum number of cars that can be parked).

---

### 🍳 Quality Feature

* **`calidad_de_la_cocina_Excelente`**
  Binary categorical variable indicating kitchen quality:

  * `1` → Excellent
  * `0` → Otherwise

---

### 🎯 Target Variable

* **`precio_de_venta`**
  Sale price of the property (in Brazilian Reais).
  This is the **dependent variable** that we aim to predict using the other property attributes.

---

## 🎯 Learning Objectives

By completing this project, you will:

* Identify linear relationships between features and house prices
* Distinguish between explanatory and response variables
* Fit a Linear Regression model
* Interpret regression coefficients
* Evaluate model performance using appropriate metrics
* Make predictions on new data
* Understand how property characteristics influence pricing

---

## 🛠 Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Statsmodels
* Google Colab

---

## 📈 Project Goal

The ultimate goal of this project is to demonstrate how **Linear Regression can be applied to real estate pricing problems**, providing insights into which features most strongly influence property values and enabling data-driven pricing decisions.

---






