# Data Science Portfolio

This repository contains a collection of data science projects focused on Exploratory Data Analysis (EDA) and Predictive Modeling. The projects utilize a variety of datasets including real estate, electric vehicles, and hospitality to demonstrate machine learning techniques.

## Project Structure

The repository is organized into three main analysis notebooks and their corresponding datasets:

1.  **Electric Vehicle Population Analysis**
    * `Electric Vehicle Population.ipynb`
    * `Electric_Vehicle_Population_Data.csv`
2.  **House Price Prediction**
    * `House Price Prediction.ipynb`
    * `house_price_dataset.csv`
3.  **USA AirBnB Market Analysis**
    * `USA-AIRBNB.ipynb`
    * `USA_AirBnB.csv`

---

## 1. Electric Vehicle Population Analysis
This project analyzes the distribution and characteristics of electric vehicles (EVs) in Washington State.
* **Objective:** Predict the **Electric Range** of vehicles based on features like Make, Model Year, and MSRP.
* **Techniques Used:** * EDA with treemaps (using `squarify`) and geographic visualization.
    * Data preprocessing: Label Encoding and Z-score outlier detection.
    * Models: RandomForestRegressor, Support Vector Regression (SVR), LightGBM, and Deep Learning (TensorFlow).
* **Key Results:** Achieved high R² scores with Gradient Boosting and Neural Network models.

## 2. House Price Prediction
A regression project aimed at estimating property values based on structural and environmental features.
* **Objective:** Predict house **Price**.
* **Key Features:** Square footage, bedrooms, bathrooms, year built, lot size, and presence of a pool.
* **Models:** Comparison between traditional Scikit-Learn regressors and advanced LightGBM/TensorFlow implementations.

## 3. USA AirBnB Analysis
An exploration of the AirBnB market across various US cities, focusing on pricing dynamics.
* **Objective:** Predict listing **Price** based on room type, location, and host statistics.
* **Techniques Used:**
    * Data cleaning: Handling missing values and removing outliers using Shapiro-Wilk tests for normality.
    * Visualization: 3D plots, room type distributions, and correlation matrices.
    * Models: RandomForest, SVR, and TensorFlow Neural Networks.

---

## Requirements

The following libraries are required to run these notebooks:
* `pandas`, `numpy` (Data Handling)
* `matplotlib`, `seaborn`, `squarify` (Visualization)
* `scikit-learn` (Machine Learning)
* `lightgbm` (Gradient Boosting)
* `tensorflow` (Deep Learning)
* `geopandas` (Geographic Analysis - for EV project)

## How to Run
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn lightgbm tensorflow squarify geopandas missingno
