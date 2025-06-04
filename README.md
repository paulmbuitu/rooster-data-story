# 📊 Rooster Data Story – Pricing Optimization & Customer Retention

## 🧠 Project Overview

Rooster aims to **optimize profitability** by transitioning from a volume-based sales strategy to a **profit-focused model**. This project leverages customer and transaction data to:

- Identify high-value customer segments  
- Predict customer retention  
- Support smarter, data-driven pricing strategies  
- Reduce out-of-stock issues through improved forecasting  

**Tools used:** `Python`, `Pandas`, `Scikit-learn`, `Tableau`

---

## 📁 Dataset Summary

The dataset included:

- `orders`  
- `products`  
- `customers`  
- `pricing history`  

After cleaning and merging, I worked with **20,000+ transactions**, performing **exploratory analysis**, **predictive modeling**, and **visual storytelling**.

---

## 📌 Key Insights

### 1. 💰 Price vs. Profit

- **15 Pack Build Your Own** and **10 Pack** products had the **highest margins and profits**.  
- **XL, L, and XXL** pack sizes drove the bulk of profits.  
- Sizes like **XS** and **6XL** contributed little to overall profitability.  

### 2. 🌍 Regional Retention Patterns

- **Intl Zone C** and **South Australia**: Highest average **return probabilities** – ideal for **loyalty programs**.  
- **New Zealand** and **Australian Capital Territory**: Strong **retention rates**, especially among **male** and **unknown-gender** customers.

---

## 🤖 Predictive Models

### 🔎 Classification – Customer Retention

- **Model:** Random Forest Classifier  
- **Features used:** `days_active`, `total_units`, `total_cost`  
- **Performance:** High precision and recall  
- **Purpose:** Accurately predicts **repeat customers** for targeted retention efforts  

### 📈 Regression – Profit Forecasting

- **Model:** Random Forest Regressor  
- **RMSE:** `8.52`  
- **R² Score:** `0.85`  
- **Key predictors:** `total_cost`, `total_units`  
- **Purpose:** Forecasts long-term customer value for better resource planning  

---

## 📊 Tableau Dashboard Highlights

1. **Return Probability by Region**  
   → Identifies regions to focus **retention campaigns**  
2. **Price vs Profit by Category**  
   → Highlights product categories with the **highest margins**  
3. **Profit by Pack Size**  
   → Shows which pack sizes generate the **most profit**  

---

## ✅ Recommendations

- 🎯 Target customers buying **10/15 Packs**, especially in **XL and L** sizes.  
- 📍 Focus retention campaigns in **New Zealand** and **Australian Capital Territory**.  
- 💡 Implement **dynamic pricing tiers** to encourage **bulk purchases**.  
- 🤝 Launch loyalty programs in **Intl Zone C** and **South Australia**.  
- 🔍 Use predictive models to prioritize **high-value customers** in marketing and inventory planning.  

---

## 🛠️ Tools & Tech

- `Python`: Data cleaning, analysis, modeling  
- `Scikit-learn`: Classification and regression  
- `Tableau`: Dashboard creation and insights  
- `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`: Data wrangling & EDA  

---

