# EDA-on-E-Commerce-Products-Categories-Prices-Reviews

# 📊 E-Commerce Product Analysis

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on an e-commerce dataset to uncover patterns in **prices, discounts, ratings, and categories**.  
The aim is to identify relationships between features, highlight trends in customer ratings, and understand how discounts and categories influence product popularity.

---

## 🗂 Dataset
The dataset includes:
- **Product category** (main and sub-categories)
- **Actual price** (original price)
- **Discounted price**
- **Discount percentage**
- **Ratings and rating count**

---

## 📈 Analysis & Visualizations

### 1️⃣ Category Distribution
- *Electronics*, *Computers & Accessories*, and *Home & Kitchen* dominate the market share.
- Electronics hold the **largest share (~36%)**, followed by Computers & Accessories (~31%) and Home & Kitchen (~30%).

### 2️⃣ Rating Distribution
- Most products have ratings between **4.0 and 4.3**.
- Few products have extremely low or perfect ratings.

### 3️⃣ Price Distribution
- Most products are priced below **₹10,000**, with a few high-priced outliers.
- Price distribution is **right-skewed**, showing many affordable products and a small number of luxury/high-end items.

### 4️⃣ Discount Analysis
- Products with **lower ratings** tend to have **higher discounts**.
- There is a **negative correlation** between discount percentage and rating.
- Most discounts range between **30% and 60%**.

### 5️⃣ Correlation Insights
- **Actual price** and **discounted price** are **strongly correlated** (correlation ≈ 0.96).
- Discount percentage has a **weak negative correlation** with ratings.
- Rating count is not strongly correlated with price or discount.

---

## 📊 Key Plots
- **Pie Chart** – Market share by category.
- **Bar Plot** – Top categories by rating count.
- **Box Plot** – Discount percentage vs rating.
- **Scatter Plots** – Relationship between actual price, discounted price, discount percentage, and ratings.
- **Correlation Heatmap** – Feature relationships.

---

## 📝 Conclusion
From the analysis, we can conclude that:
1. **Electronics** dominate the product listings, followed closely by **Computers & Accessories** and **Home & Kitchen**.
2. **Higher discounts** are often applied to **lower-rated products**, possibly as a strategy to boost sales.
3. **Price does not strongly influence ratings**, suggesting quality and customer experience matter more than cost.
4. **Most products** are in the affordable range, with only a small fraction being high-end luxury items.
5. **Discount percentage and rating** show a mild inverse relationship, indicating that higher-rated products may not rely heavily on discounts.
6. The strong correlation between **actual and discounted price** confirms a consistent pricing strategy across categories.

---

## 🚀 Future Work
- Apply **predictive modeling** to forecast ratings based on product features.
- Segment products by **brand** to identify brand-specific pricing and rating trends.
- Explore **seasonal patterns** in discounts and sales.
