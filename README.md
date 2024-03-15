Weather Prediction with SVM and Random Forest

This repository contains code and data for predicting weather conditions based on meteorological features in Sri Lanka. We’ll use the SVM and Random Forest algorithms to tackle this task.

Problem Definition
Task (T): Predicting the weather according to climate conditions.
Experience (E): Meteorological data and weather-related features of Sri Lanka.
Performance Measure (P): Accuracy, Multiclass log loss.

Data

Data Source: Sri Lanka Weather Dataset on Kaggle

Features:
Time
Weather Code
Maximum Temperature
Minimum Temperature
Mean 2-meter Temperature
Maximum Apparent Temperature
Minimum Apparent Temperature
Mean Apparent Temperature
Sunrise Time
Sunset Time
Total Shortwave Radiation
Total Precipitation
Total Rainfall
Total Snowfall
Precipitation Hours
Maximum Wind Speed
Maximum Wind Gusts
Dominant Wind Direction
Reference Evapotranspiration
Latitude
Longitude
Elevation
Country
City

Number of Features: 24
Dataset Size: 147,486 records

Handling Missing Data
Missing data will be handled by imputation or exclusion based on the number of missing values:
For numerical values, mean imputation will be used.
For categorical values, mode imputation will be applied.

Algorithms
  a. Algorithms
Support Vector Machines (SVM)
Random Forest
  b. Availability in Libraries

Both algorithms are readily available in the scikit-learn library for Python
