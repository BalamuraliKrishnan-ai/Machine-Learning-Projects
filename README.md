# 🏠 House Price Prediction using Machine Learning

A supervised machine learning project to predict house prices using various features from a real estate dataset.

---

## 📌 Project Overview

This project uses a housing dataset to predict house prices based on features like area, number of bedrooms, bathrooms, and furnishing status. We apply machine learning regression techniques to model the price accurately.

---

## 📊 Dataset Description

- **File**: `Housing.csv`
- **Total Entries**: 500+
- **Features**:
  - `area` — size of the house (in sq. ft)
  - `bedrooms` — number of bedrooms
  - `bathrooms` — number of bathrooms
  - `stories` — number of floors
  - `mainroad` — whether the house is on the main road (yes/no)
  - `guestroom` — availability of guestroom (yes/no)
  - `basement` — has basement (yes/no)
  - `hotwaterheating` — has hot water heating (yes/no)
  - `airconditioning` — has air conditioning (yes/no)
  - `parking` — number of parking spots
  - `prefarea` — preferred area (yes/no)
  - `furnishingstatus` — furnished/semi-furnished/unfurnished
  - `price` — target variable (price of the house)

---

## 🧰 Tech Stack

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-Learn

---

## 🧠 ML Techniques Used

- Data preprocessing:
  - Label encoding of categorical variables
  - Missing value handling
  - Feature scaling
- Model training:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Model evaluation:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

---

## 📈 EDA Highlights

- Correlation heatmap to identify most impactful features
- Price distribution and comparison by furnishing status
- Impact of air conditioning, preferred area, and main road on price

---

## 📁 Folder Structure

