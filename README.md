# 🚗 Car Price Prediction using Machine Learning

A Machine Learning project that predicts the **selling price of used cars** based on features such as brand, fuel type, transmission, mileage, engine capacity, and more.

This project uses **Random Forest Regression** and provides a simple **Gradio web interface** for real-time predictions.

---

## 📌 Project Overview

Buying and selling used cars often relies on manual estimation.
This project builds a data-driven prediction system that helps estimate fair car prices.

### Main Goals

* Perform data preprocessing and feature engineering
* Train and compare multiple ML models
* Select the best model based on performance
* Deploy a simple web interface for users

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Gradio
* Jupyter Notebook

---

## 📊 Dataset

Dataset: **CarDekho Used Car Dataset**

Main features used:

* Brand
* Vehicle Age
* Kilometers Driven
* Fuel Type
* Transmission Type
* Mileage
* Engine Capacity
* Number of Seats

Target variable:

* Selling Price

---

## ⚙️ Data Preprocessing

* Removed unnecessary columns (e.g. model)
* Label Encoding for categorical features:

  * Brand
  * Fuel Type
  * Transmission
* Train-Test Split applied

---

## 🤖 Model Training

Models tested:

* Multiple Linear Regression
* Random Forest Regressor

Final Model:

* **Random Forest Regressor**

Performance (R² Score):

| Model             | Train Score | Test Score |
| ----------------- | ----------- | ---------- |
| Linear Regression | 0.85        | 0.82       |
| Random Forest     | 0.97        | 0.90       |

---

## 💾 Saved Model Files

* car_price_model.pkl
* fuel_encoder.pkl
* trans_encoder.pkl
* brand_encoder.pkl

These are loaded directly inside `app.py`.

---

## 🌐 Web Application (Gradio)

A simple UI built with Gradio allows users to:

* Enter car details
* Predict selling price instantly

Run locally:

```bash
python app.py
```

---

## ▶️ How to Run This Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/SanjanaMargam/CarPricePrediction.git
cd CarPricePrediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run App

```bash
python app.py
```

---

## 📈 Future Improvements

* Deploy on HuggingFace / Render
* Use advanced models (XGBoost, CatBoost)
* Add image-based car condition analysis
* Real-time data integration

---

## 👩‍💻 Author

**Sanjana Margam**

GitHub: https://github.com/SanjanaMargam
