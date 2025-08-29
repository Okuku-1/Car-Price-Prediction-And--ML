# Car Price Prediction 🚗💰

This project focuses on analyzing and preparing a car resale dataset to build a **machine learning model** that predicts car prices. The notebook covers data cleaning, preprocessing, feature engineering, and exploratory data analysis (EDA).

---

## 📂 Dataset Overview
The dataset (`cardekho.csv`) contains used car listings with attributes such as:
- **name** – Car model name (brand + variant)  
- **year** – Manufacturing year  
- **selling_price** – Target variable, car resale value (in INR ₹)  
- **km_driven** – Kilometers driven  
- **fuel** – Fuel type (Petrol, Diesel, CNG, etc.)  
- **seller_type** – Type of seller (Individual, Dealer, Trusted Dealer)  
- **transmission** – Manual or Automatic  
- **owner** – Ownership history (First, Second, etc.)  
- **mileage, engine, max_power, seats** – Technical specifications  

---

## 🔎 Data Cleaning & Preprocessing
Steps performed:
1. **Handle Missing Values**  
   - Dropped rows with missing target (`selling_price`).  
   - Imputed missing `mileage` values with column mean.  

2. **Duplicates**  
   - Removed duplicate rows to avoid bias in training.  

3. **Feature Engineering**  
   - Converted `year` → `car_age` for better prediction.  
   - Normalized categorical columns (`fuel`, `seller_type`, `transmission`, `owner`).  

4. **Consistency Checks**  
   - Fixed inconsistent casing in categorical features.  
   - Verified unique values before encoding.  

---

## 📊 Exploratory Data Analysis
- Distribution of selling prices, mileage, and engine sizes.  
- Relationship between car age, kilometers driven, and resale value.  
- Impact of fuel type and transmission on price.  

---

## 🤖 Modeling Potential
- Supervised learning: Regression models (Linear Regression, Random Forest, Gradient Boosting).  
- Feature importance analysis for price drivers.  
- Potential extension: Deploy as a price prediction web app.  

---
