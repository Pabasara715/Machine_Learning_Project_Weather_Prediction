# 🌦️ Weather Prediction with SVM and Random Forest

This project focuses on **predicting weather conditions in Sri Lanka** using machine learning models. We leverage **Support Vector Machines (SVM)** and **Random Forests** to classify weather based on meteorological features.  

The goal is to enhance **climate insights** through data-driven approaches, supporting better weather understanding and forecasting.

---

## 📌 Problem Definition

- **Task (T):** Predicting weather conditions from climate features  
- **Experience (E):** Historical meteorological data from Sri Lanka  
- **Performance Measure (P):** Accuracy, Multiclass Log Loss  

---

## 📊 Dataset

- **Source:** [Sri Lanka Weather Dataset – Kaggle](https://www.kaggle.com)  
- **Records:** 147,486  
- **Features:** 24 (climate & geographical attributes)  

**Key Features:**
- Weather Code, Time, Sunrise, Sunset  
- Maximum / Minimum / Mean Temperature  
- Apparent Temperatures  
- Precipitation, Rainfall, Snowfall  
- Radiation & Evapotranspiration  
- Wind Speed, Gusts, Direction  
- Latitude, Longitude, Elevation, City, Country  

---

## 🧹 Data Preprocessing

- **Handling Missing Data:**  
  - Numerical → *Mean Imputation*  
  - Categorical → *Mode Imputation*  
- **Feature Scaling & Encoding** applied as needed for model compatibility  

---

## 🤖 Machine Learning Models

We used two powerful algorithms from **Scikit-learn**:

1. **Support Vector Machines (SVM)**  
   - Effective for high-dimensional data  
   - Works well with complex decision boundaries  

2. **Random Forest**  
   - Ensemble learning technique  
   - Robust to noise & handles large datasets efficiently  

---

## 📈 Performance Metrics

- **Accuracy** – percentage of correctly predicted weather conditions  
- **Multiclass Log Loss** – evaluates predictive probabilities  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:**  
  - `scikit-learn` – Machine Learning  
  - `pandas` – Data Handling  
  - `numpy` – Numerical Computation  
  - `matplotlib`, `seaborn` – Visualization  


