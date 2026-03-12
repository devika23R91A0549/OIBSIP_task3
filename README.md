# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Description

Car price prediction is an important application of machine learning in the automobile industry. The price of a used car depends on multiple factors such as the manufacturing year, kilometers driven, fuel type, transmission type, and number of previous owners.

This project analyzes a **Used Car Dataset from Kaggle** and builds a **Machine Learning model** to predict the selling price of a car based on its features.

---

## 📂 Dataset

The dataset used in this project is **Car Price Prediction (Used Cars)** from Kaggle.

### Dataset Features

| Feature       | Description                    |
| ------------- | ------------------------------ |
| Car_Name      | Name of the car                |
| Year          | Year of manufacture            |
| Selling_Price | Price at which the car is sold |
| Present_Price | Current ex-showroom price      |
| Driven_kms    | Total kilometers driven        |
| Fuel_Type     | Petrol / Diesel / CNG          |
| Selling_type  | Dealer or Individual           |
| Transmission  | Manual or Automatic            |
| Owner         | Number of previous owners      |

---

## 🔍 Exploratory Data Analysis (EDA)

Data visualization techniques were used to understand the dataset and identify patterns.

Visualizations included:

* 📊 Bar Charts
* 📉 Histograms
* 📈 Scatter Plots
* 📦 Box Plots
* 🔥 Correlation Heatmaps
* 🥧 Pie Charts
* 🔗 Pair Plots

Key insights discovered:

* Cars with **higher kilometers driven usually have lower selling prices**
* **Newer cars tend to have higher prices**
* **Dealer cars often have higher selling prices compared to individual sellers**

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🧠 Machine Learning Model

The model used for prediction:

**Linear Regression**

### Steps involved

1. Data preprocessing
2. Feature encoding
3. Train-test split
4. Model training
5. Model prediction
6. Model evaluation using **R² Score**

---

## 📊 Model Evaluation

The model performance was evaluated using **R² Score**, which measures how well the predicted values match the actual selling prices.
