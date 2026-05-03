# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project focuses on analyzing customer shopping behavior using transactional data of **3,900 purchases** across multiple product categories.  
The main goal is to uncover insights into:
- Customer spending patterns  
- Product preferences  
- Subscription behavior  
- Customer segmentation  

These insights help businesses make better data-driven decisions.

---

## 📊 Dataset Summary
- **Total Rows:** 3,900  
- **Total Columns:** 18  

### Key Features:
- **Customer Info:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Amount, Season, Size, Color  
- **Behavior Data:** Discount Applied, Promo Code, Previous Purchases, Frequency, Ratings, Shipping Type  

- **Missing Data:**  
  - 37 missing values in *Review Rating*

---

## 🧹 Data Cleaning & Preparation (Python)
Performed using **Pandas**

- Loaded dataset and explored using `.info()` and `.describe()`  
- Handled missing values using **median imputation (category-wise)**  
- Renamed columns into **snake_case**  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column: `promo_code_used`  
- Loaded cleaned data into **PostgreSQL**

---

## 🗄️ SQL Analysis (Business Insights)

Performed analysis using SQL queries:

1. **Revenue by Gender**
2. **High-Spending Discount Users**
3. **Top 5 Products by Rating**
4. **Shipping Type Comparison**
5. **Subscribers vs Non-Subscribers**
6. **Discount-Dependent Products**
7. **Customer Segmentation (New, Returning, Loyal)**
8. **Top 3 Products per Category**
9. **Repeat Buyers vs Subscription Behavior**
10. **Revenue by Age Group**

---

## 📈 Power BI Dashboard

An interactive dashboard was created to visualize insights.

### Key Metrics:
- Total Customers: **3.9K**
- Average Purchase Amount: **$59.76**
- Average Rating: **3.75**

### Visualizations:
- Revenue by Category  
- Sales by Category  
- Revenue by Age Group  
- Sales by Age Group  
- Subscription Distribution  

---

## 🔍 Key Insights

- Male customers generated higher revenue than female customers  
- Discount users can still be high spenders  
- Some products depend heavily on discounts  
- Loyal customers form the largest segment  
- Young adults contribute highest revenue  
- Subscription does not always mean higher spending  

---

## 💡 Business Recommendations

- Increase subscription benefits to attract users  
- Reward loyal customers with offers  
- Optimize discount strategy to maintain profit  
- Promote top-rated products  
- Target high-value age groups  
- Focus marketing on express shipping users  

---

## 🛠️ Tools & Technologies

- **Python (Pandas, NumPy)**  
- **PostgreSQL (SQL)**  
- **Power BI**  

---

## 🚀 Conclusion

This project demonstrates how raw transactional data can be transformed into meaningful business insights using data analysis and visualization tools.

---
