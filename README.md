# 🚕 Uber Fare Prediction — New York City

> Predicting Uber ride fares using Machine Learning with an interactive map-based Streamlit app.

---

## 📌 Project Overview

This project builds an end-to-end machine learning system to predict Uber ride fares
in New York City. It covers the full data science pipeline : data cleaning, feature 
engineering, model training, clustering analysis, and deployment via an interactive 
Streamlit application.

---

## 🚀 Demo

### Streamlit Application — Interactive Map & Real-time Fare Prediction
![Streamlit App](image1.PNG)

---

## 📊 Models & Results

### Supervised Learning — Fare Prediction

| Model | R² |
|-------|-----|
| **Gradient Boosting** | **Best** |
| XGBoost | ✅ |
| Random Forest | ✅ |
| KNN (Chebyshev) | ✅ |
| Linear Regression | Baseline |

✅ **Best model : Gradient Boosting** — deployed in the Streamlit app

### Unsupervised Learning — Trip Segmentation
- Applied **KMeans clustering** to segment trips into 3 categories :
  - 🟢 Short trips (< 5 km)
  - 🟡 Medium trips (5–12 km)
  - 🔴 Long trips (> 12 km)

---

## 🗺️ App Features

- 📍 Interactive **Folium map** — click to select Pickup and Dropoff points
- 🛣️ Real route calculation via **OpenRouteService API**
- 💵 Instant fare prediction using **Gradient Boosting**
- 👥 Configurable passenger count

---

## 🛠️ Tech Stack

- **Language :** Python
- **ML Models :** Scikit-learn, XGBoost, Grad
