# Car-Price-Prediction-Project

##  Project Objective

To build an accurate and efficient machine learning model to predict car selling prices using structured data containing various car features.

---

## 🧾 Dataset Description

The dataset includes the following features:

- Car Name: Brand and model of the car
- Year: Year of manufacture
- Present_Price: Current ex-showroom price
- Kms_Driven: Distance driven in kilometers
- Fuel_Type: Petrol, Diesel, or CNG
- Seller_Type: Dealer or Individual
- Transmission: Manual or Automatic
- Owner: Number of previous owners
- Selling_Price: (Target) Price at which the car is being sold

---

## 🔧 Tools & Technologies Used

- Programming Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, pickle
- Jupyter Notebooks: For development and testing

---

## 📊 Exploratory Data Analysis (EDA)

Performed in EDA 2 (1).ipynb:

- Checked for null and duplicate values
- Analyzed feature distributions
- Examined correlations between features
- Identified key factors influencing selling price (e.g., Year, Present_Price, Kms_Driven)

---

## 🛠 Data Preprocessing

Performed in 01-Data Cleaning.ipynb:

- Removed unnecessary columns
- Converted categorical data to numerical using one-hot encoding
- Scaled features where necessary
- Saved the cleaned data in new cleaned car data.csv

---

## 🤖 Machine Learning Models Used

Evaluated various models in Model Selection.ipynb and Using Other Algorithm.ipynb:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Best Performing Model:  
 Random Forest Regressor

---

## 🏆 Model Performance

- Random Forest Regressor
  - R² Score: ~0.91
  - Root Mean Squared Error (RMSE): Low
- Final Model File: CarProject (1).pkl
- Alternative Models: CarProjectUsing_other_algos.pkl

---

## 📦 How to Use the Model

1. Load the .pkl file using Python's pickle module.
2. Pass car feature values as input.
3. Get the predicted selling price as output.
