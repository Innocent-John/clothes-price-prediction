# 👕 Clothing Price Prediction Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Project-Price%20Prediction-blue" />
  <img src="https://img.shields.io/badge/Tool-Excel%20%7C%20WPS-green" />
  <img src="https://img.shields.io/badge/Analysis-Regression-orange" />
  <img src="https://img.shields.io/badge/Dataset-1000%20Records-lightgrey" />
</p>

---<img width="4096" height="4096" alt="Image" src="https://github.com/user-attachments/assets/f27a7e99-2686-4e78-bd2b-18eece16ac08" />

## 📌 Project Overview

This project analyzes clothing prices using structured data and statistical techniques to identify key factors influencing pricing.
The analysis focuses on **Brand, Category, Material, and Size**, and applies **descriptive statistics and regression concepts**.

---

## 🎯 Business Questions

1. What is the average clothing price by **Brand and Category**?
2. Which **material** drives higher clothing prices?
3. Which **brand** has the highest average price?
4. Does **size** affect price?
5. Which **category** generates the highest revenue potential?

---

## 📂 Dataset Summary

* Total Records: **1000**
* Features:

  * Brand
  * Category
  * Material
  * Size
  * Price

---

## ⚙️ Methodology (Workflow)

### 🔹 Step 1: Data Preparation

* Cleaned dataset
* Structured data into tabular format
* Converted categorical variables where necessary

### 🔹 Step 2: Exploratory Data Analysis (EDA)

* Used **Pivot Tables** to summarize:

  * Average price by brand & category
  * Average price by material
  * Average price by size

### 🔹 Step 3: Aggregation & Insights

* Compared averages across groups
* Identified trends and pricing patterns

---

## 📊 Analysis & Results

### ✅ Question 1: Average Price by Brand & Category

* **Dress** has the highest category average → **114.51**
* **New Balance (Dress)** → Highest segment price (**127.67**)
* **Puma (Jacket)** also shows strong pricing (**121.19**)

📌 Insight: Pricing varies significantly across both **brand and category combinations**.

---

### ✅ Question 2: Material Driving Higher Prices

| Material  | Avg Price |
| --------- | --------- |
| Nylon     | 109.39    |
| Wool      | 109.20    |
| Denim     | 107.69    |
| Polyester | 106.43    |
| Cotton    | 103.35    |
| Silk      | 101.91    |

📌 Insight: **Nylon and Wool** drive the highest clothing prices.

---

### ✅ Question 3: Highest Average Price by Brand

| Brand        | Avg Price |
| ------------ | --------- |
| New Balance  | 115.46    |
| Reebok       | 106.49    |
| Puma         | 106.14    |
| Adidas       | 104.05    |
| Under Armour | 103.96    |
| Nike         | 101.91    |

📌 Insight: **New Balance** is the premium-priced brand in this dataset.

---

### ✅ Question 4: Does Size Affect Price?

| Size | Avg Price |
| ---- | --------- |
| XS   | 110.12    |
| XXL  | 109.34    |
| L    | 106.16    |
| M    | 105.19    |
| S    | 103.90    |
| XL   | 102.15    |

📌 Insight:

* Smaller (**XS**) and larger (**XXL**) sizes tend to have slightly higher prices
* However, **size has a weak overall impact** compared to brand and category

---

### ✅ Question 5: Revenue Potential by Category

| Category | Count | Avg Price |
| -------- | ----- | --------- |
| Jacket   | 191   | 102.83    |
| Shoes    | 172   | 108.57    |
| Jeans    | 167   | 100.75    |
| Dress    | 166   | 114.51    |
| Sweater  | 160   | 106.78    |
| T-shirt  | 144   | 104.56    |

📌 Insight:

* **Dress** → Highest price (premium category)
* **Jacket** → Highest volume (191 items)
* 👉 Combining both, **Dress and Jacket offer strong revenue potential**

---

## 📈 Key Findings

* 🏷️ **Brand is the strongest driver of price**
* 👗 **Category significantly impacts pricing**
* 🧵 **Material has moderate influence (Nylon & Wool highest)**
* 📏 **Size has minimal effect on pricing**
* 💰 **Revenue potential depends on both price and quantity**

---

## 🛠️ Tools Used

* Microsoft Excel / WPS Office
* Pivot Tables
* Descriptive Statistics

---

## 🚀 Future Improvements

* Apply **Regression Analysis** for prediction modeling
* Use **Python (Pandas, Scikit-learn)**
* Build **machine learning models**
* Add more features (season, ratings, discounts)

---

## 📎 How to Reproduce

1. Load dataset into Excel
2. Create Pivot Tables
3. Group by:

   * Brand & Category
   * Material
   * Size
4. Calculate average price
5. Interpret insights

---

## 👤 Author

**Innocent John**
📊 Data Analysis Project

---

## ⭐ Support

If you found this project useful, please ⭐ the repository!

