# EDA-House_rentals
# 🏠 House Rental Price Analysis – EDA Project

## 📊 Overview

This repository contains an Exploratory Data Analysis (EDA) of a house rental dataset. The goal is to identify the major factors that influence rental prices across different cities using data cleaning, visualization, and feature interpretation.

---

## 🔍 Project Objectives

* Clean and preprocess the rental dataset.
* Explore trends and correlations affecting rent.
* Analyze how features like **city**, **BHK**, **size**, and **furnishing type** impact rental values.
* Build a foundation for predictive modeling and market insights.

---

## 🗂️ Dataset Features

| Feature           | Description                              |
| ----------------- | ---------------------------------------- |
| `city`            | City where the house is located          |
| `bhk`             | Number of bedrooms                       |
| `furnishing_type` | Furnished / Semi-furnished / Unfurnished |
| `size`            | Area in square feet                      |
| `rent`            | Monthly rental price                     |
| `bath`            | Number of bathrooms                      |

---

## 🧹 Data Cleaning Steps

* Removed duplicates
* Handled missing values
* Standardized categorical text
* Converted data types
* Identified and treated outliers

---

## 📈 Visualizations Included

* Rental price distribution
* City-wise rent comparison
* BHK vs rent analysis
* Furnishing-type impact on rent
* Correlation heatmap for numerical features

---

## 🧠 Key Insights

* Rental prices vary significantly across cities.
* Higher BHK count and larger area result in higher rents.
* Furnished houses usually demand higher rental prices.
* City and furnishing type are strong predictors of rental value.

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```
house-rental-eda/
│── data/
│   └── house_rent_data.csv
│── notebooks/
│   └── EDA_House_Rental.ipynb
│── visuals/
│   └── charts & plots
│── README.md
│── requirements.txt
```

---

## 🚀 How to Run

```
git clone https://github.com/Harish-img/house-rental-eda
cd house-rental-eda
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Future Enhancements

* Build predictive machine learning models
* Feature engineering for better insights
* Deploy analysis using Streamlit or Flask

---

## ✨ Author

**Harish Pentapalli**
B.Tech CSE (Cyber Security) | Data Analyst | ML Enthusiast

---
