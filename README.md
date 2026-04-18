# 🚗 Car Price Prediction using Machine Learning

---

## 📌 Overview

This project focuses on predicting the **selling price of used cars** using machine learning techniques.
The goal is to analyze key features such as vehicle age, price, fuel type, and usage to build a reliable regression model.

---

## 🎯 Objective

* Predict car selling price based on historical data
* Understand factors influencing car valuation
* Apply end-to-end ML workflow (EDA → preprocessing → modeling → evaluation)

---

## 📊 Dataset

* Contains **300+ car records** with features like:

  * Year of purchase
  * Present price
  * Kilometers driven
  * Fuel type
  * Seller type
  * Transmission
  * Owner count

> Dataset cleaned by removing duplicates and handling categorical variables.

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked missing values (none found)
* Removed duplicate records
* Visualized:

  * Category distributions (Fuel, Seller, Transmission)
  * Outliers using boxplots
  * Feature correlations using heatmap

### 📈 Key Insight

* **Present Price** has the strongest correlation with Selling Price
* Vehicle age has moderate impact
* Kilometers driven has weak correlation

---

## ⚙️ Data Preprocessing

* Dropped unnecessary column: `Car_Name`
* Applied **Label Encoding** to categorical variables
* Split data into:

  * Training set (75%)
  * Testing set (25%)

---

## 🧠 Model Used

### Linear Regression

* Simple and interpretable regression model
* Trained on processed dataset

---

## 📉 Model Performance

* **R² Score:** ~85%
* **Mean Squared Error (MSE):** 2.60
* **Mean Absolute Error (MAE):** 1.14

---

## 📊 Visualization

* Regression plot comparing actual vs predicted values
* Shows strong alignment with some outliers

---

## 🚀 How to Run

```bash id="run1"
git clone https://github.com/RajeevKumar-Me/car-price-prediction-ml.git
cd car-price-prediction-ml
pip install -r requirements.txt
```

Run notebook:

```bash id="run2"
jupyter notebook
```

---

## 📁 Project Structure

```bash id="run3"
car-price-prediction-ml/
│
├── notebooks/
│   └── car_price_prediction.ipynb
├── README.md
└── requirements.txt
```


## ⭐ Conclusion

This project demonstrates the complete machine learning pipeline—from raw data analysis to building a predictive model.
It highlights how data-driven approaches can be used to estimate real-world values like car prices.
