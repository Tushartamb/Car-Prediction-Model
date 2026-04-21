# 🚗 Car Price Prediction Model</b>

## 📌 Project Overview</b>

This project focuses on building a **Machine Learning model to predict car prices** based on various features. The goal is to create an accurate regression model using real-world data and proper preprocessing techniques.</b>

---</b>

## 📂 Dataset</b>

* Source: Kaggle</b>
* Size: **6020 rows**</b>
* The dataset contains different car attributes such as price, engine, mileage, etc.</b>

---</b>

## 🛠️ Steps Performed</b>

### 1. Data Loading</b>

* Imported dataset using **pandas**</b>

### 2. Data Cleaning</b>

* Removed **null values**
* Removed **extra characters** from columns (like units: km/kg, cc, bhp)</b>
* Cleaned text data for better processing</b>

### 3. Feature Engineering</b>

* Removed values with **very low frequency (noise reduction)**</b>
* Encoded categorical variables using **Label Encoding**</b>

### 4. Data Preparation</b>

* Split data into:</b>

  * **Independent features (X)**</b>
  * **Dependent feature (y)**</b>
* Performed **train-test split**</b>

### 5. Data Scaling</b>

* Applied **Standardization** using `StandardScaler`</b>

---</b>

## 🤖 Model Used</b>

* **Random Forest Regressor**</b>

Why Random Forest?</b>

* Handles non-linear relationships well</b>
* Provides high accuracy</b>
* Works well with mixed data</b>

---

## 📊 Model Performance</b>

* **Training Accuracy (R² Score):** 98%</b>
* **Testing Accuracy (R² Score):** 94%</b>

👉 The model performs well with minimal overfitting.</b>

---</b>

## 📈 Visualization</b>

* Plotted **Actual vs Predicted values** using line charts</b>
* Helps in understanding model performance visually</b>

---</b>

## 🚀 Technologies Used</b>

* Python</b>
* Pandas</b>
* NumPy</b>
* Scikit-learn</b>
* Matplotlib</b>

---</b>

## ⚠️ Future Improvements</b>

* Try **XGBoost / Gradient Boosting**</b>
* Perform **hyperparameter tuning**</b>
* Use **feature selection techniques**</b>
* Deploy model using **Flask or Streamlit**</b>

---</b>

## 📌 Conclusion</b>

This project demonstrates a complete **Machine Learning pipeline**:</b>

* Data Cleaning</b>
* Feature Engineering</b>
* Model Training</b>
* Evaluation</b>

The model achieves strong performance and can be further improved with advanced techniques.</b>

---
