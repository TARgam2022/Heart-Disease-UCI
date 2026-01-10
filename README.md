# Heart Disease Prediction (UCI)

This repository contains a machine learning project for predicting heart disease using the **UCI Heart Disease Dataset**. The dataset originates from the **UCI Machine Learning Repository**, a widely used public dataset for benchmarking classification models in health and medical domains. :contentReference[oaicite:0]{index=0}

---

## 📌 Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection through machine learning models can support clinicians in identifying high-risk patients and improve patient outcomes. This project uses classic machine learning techniques to build a classification model that predicts whether a patient has heart disease based on clinical and demographic features.

---

## 📋 Dataset Description

The dataset includes patient attributes such as age, blood pressure, cholesterol levels, and other relevant clinical measurements. While the full UCI repository contains more attributes, this project uses a commonly accepted subset of 14 attributes that have been most widely used in research. :contentReference[oaicite:1]{index=1}

### Input Features

The 13 most important attributes used include:

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise induced angina (exang)
- ST depression relative to rest (oldpeak)
- Slope of the ST segment (slope)
- Number of major vessels colored by fluoroscopy (ca)
- Thalassemia type (thal)

The target variable `target` indicates presence of heart disease:
- `0` — no heart disease
- `1` — presence of heart disease

Binary classification is used by combining all non-zero diagnosis values into a single positive class. :contentReference[oaicite:2]{index=2}
