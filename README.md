
# 🧼 Titanic Data Cleaning & Preprocessing

This project focuses on preparing the **Titanic dataset** for machine learning by cleaning and preprocessing the raw data. It covers the basic but essential steps of any ML project.

---

## 📂 Dataset Used

**Titanic Dataset** — contains information about passengers (age, sex, fare, survival, etc.) from the Titanic shipwreck.

---

## 🎯 Objective

Prepare the dataset for machine learning by:
- Handling missing values
- Encoding categorical features
- Standardizing numerical features
- Detecting and removing outliers

---

## 🔧 Tools Used

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## ✅ Steps Completed

### 1. Import and Explore Dataset
- Loaded the CSV file
- Checked null values, data types, and general info

---

### 2. Handle Missing Values
- Replaced missing **Age** values with the **mean**
- Replaced missing **Fare** values with the **median**
- Replaced missing **Embarked** values with the **mode**

---

### 3. Encode Categorical Features
- Converted `Sex` to numeric values (e.g., male = 0, female = 1)
- Encoded `Embarked` using one-hot encoding

---

### 4. Normalize/Standardize Numerical Features
- Scaled `Age` and `Fare` using standardization

---

### 5. Visualize and Remove Outliers
- Visualized outliers using boxplots
- Removed outliers using the IQR (Interquartile Range) method

---

## 📌 Final Output

- Cleaned, consistent dataset
- Ready for machine learning model training
- All values normalized and without outliers or missing data

---

## 📘 Learnings

- How to handle missing data with **mean**, **median**, **mode**
- What encoding and standardization do and why they matter
- How to find and remove outliers with **IQR and boxplots**
