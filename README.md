# 📊 Sales Data Analysis using Pandas

## 📌 Project Overview

This project performs basic sales data analysis using Python with the help of **Pandas**.
The goal is to extract meaningful insights such as revenue, product performance, and city-wise sales trends from a structured dataset.

---

## 🎯 Objectives

* Analyze total sales and revenue
* Identify best-selling products
* Perform city-wise sales analysis
* Practice real-world data analysis using Pandas

---

## 🛠️ Technologies Used

* Python
* Pandas

---

## 📂 Dataset Description

The dataset used in this project is manually created and contains the following columns:

* **Date** → Date of transaction
* **Product** → Product name (Laptop, Mobile, Tablet)
* **Price** → Price of product
* **Quantity** → Units sold
* **City** → City where sale occurred
* **Revenue** → Calculated as Price × Quantity

---

## ⚙️ Steps Performed

### 1. Data Creation & Loading

* Created dataset using Python dictionary
* Converted into Pandas DataFrame

### 2. Data Preprocessing

* Converted `Date` column to datetime format
* Created a new column **Revenue**

### 3. Data Analysis

#### 🔹 Total Revenue

Calculated overall revenue generated.

#### 🔹 Product-wise Analysis

* Total quantity sold per product
* Revenue generated per product
* Identified:

  * Most popular product (by quantity)
  * Best performing product (by revenue)

#### 🔹 City-wise Analysis

* Revenue generated per city
* Best performing city
* Product performance within each city

---

## 📈 Key Insights

* Some products sell more in quantity but generate less revenue
* High-priced products may generate more revenue despite lower sales
* Sales performance varies across cities

---

## 🧠 Learning Outcomes

Through this project, I learned:

* How to use Pandas for real-world data analysis
* Working with `groupby()` and aggregation
* Creating new calculated columns
* Performing multi-level analysis (City + Product)

---

## 🚀 Future Improvements

* Use real-world dataset instead of manually created data
* Add data visualization using Matplotlib or Seaborn
* Perform profit analysis (not just revenue)
* Build an interactive dashboard

---

## 📌 Conclusion

This project helped in building a strong foundation in data analysis using Pandas by applying concepts to a practical sales dataset.

---
