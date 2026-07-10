# Project-2: E-Commerce Sales Data Analysis using Excel (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an E-Commerce sales dataset.

The main objective of this project is to clean the dataset, analyze sales patterns, identify trends, detect outliers, and generate meaningful business insights using Microsoft Excel.

---

# 🎯 Project Objectives

The objectives of this project are:

- Perform data cleaning and preprocessing
- Analyze basic statistical information
- Identify missing values and handle them
- Analyze product-wise sales performance
- Analyze order status distribution
- Analyze payment method preferences
- Analyze customer referral sources
- Study monthly sales trends
- Detect outliers in order values
- Generate insights from the dataset

---

# 🛠 Tools Used

- Microsoft Excel
- Pivot Tables
- Excel Charts
- Excel Formulas
- Data Cleaning Techniques
- Exploratory Data Analysis (EDA)
---

# 📂 Dataset Information

The dataset contains e-commerce order details including:

- Order ID
- Order Date
- Customer ID
- Product
- Quantity
- Unit Price
- Shipping Address
- Payment Method
- Order Status
- Tracking Number
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

Total Records Analyzed:

**1200 Orders**

---

# 🧹 Data Cleaning Process

The following cleaning steps were performed:

## Missing Value Analysis

- Checked missing values in the dataset.
- Identified missing values in the CouponCode column.
- Found 309 missing coupon values.
- Replaced missing coupon values with "No Coupon".

After cleaning:
- CouponCode column contains 0 missing values.
---

# 📊 Exploratory Data Analysis

## 1. Basic Statistical Analysis

Calculated:

- Average Quantity
- Median Quantity
- Minimum Quantity
- Maximum Quantity
- Average Unit Price
- Median Unit Price
- Minimum Unit Price
- Maximum Unit Price
- Average Total Price
- Median Total Price
- Total Revenue
- Highest Order Value


### Key Results:

- Total Orders: 1200
- Average Quantity: 2.95
- Average Order Value: ₹1053.97
- Total Revenue: ₹1,264,761.96
- Highest Order Value: ₹3456.40


---

# 📈 Pivot Table Analysis

## 1. Product Analysis

Analyzed total quantity sold for each product.

### Insight:

- Best Selling Product: **Chair**
- Lowest Selling Product: **Phone**

Chart Used:

- Bar Chart


---

## 2. Order Status Analysis

Analyzed order distribution based on status:

Categories:

- Delivered
- Shipped
- Pending
- Cancelled
- Returned


Chart Used:

- Pie Chart


Insight:

- Cancelled orders have the highest count among order statuses.

---

## 3. Payment Method Analysis

Analyzed customer payment preferences.

Payment methods:

- Online
- Cash
- Credit Card
- Debit Card
- Gift Card


Chart Used:

- Pie Chart


Insight:

- Online payment is the most preferred payment method.

---

## 4. Referral Source Analysis

Analyzed where customers came from.

Sources:

- Instagram
- Email
- Google
- Facebook
- Referral


Chart Used:

- Bar Chart


Insight:

- Instagram generated the highest number of orders.

---

## 5. Monthly Sales Trend Analysis

Analyzed revenue trends month-wise.


Chart Used:

- Line Chart


Insight:

- June recorded the highest monthly revenue.

---

# 🚨 Outlier Detection

Outlier analysis was performed using:

- Q1
- Q3
- IQR Method
- Upper Limit
- Lower Limit


Results:

- Upper Limit: 3330.41
- Highest Order Value: 3456.40


Conclusion:

A high-value outlier exists in the dataset.

---

# 📌 Final Business Insights

The major findings from the analysis are:

- The dataset contains 1200 orders.
- Total revenue generated is ₹1,264,761.96.
- Average order value is ₹1053.97.
- Missing coupon values were cleaned successfully.
- Chair is the best-selling product.
- Online payment is the most used payment method.
- Instagram is the top referral source.
- June achieved the highest monthly revenue.
- High-value orders were identified through outlier analysis.


---

# 📊 Visualizations Included

The project contains:

✅ Product-wise Sales Quantity Bar Chart

✅ Order Status Distribution Pie Chart

✅ Payment Method Distribution Pie Chart

✅ Referral Source Analysis Bar Chart

✅ Monthly Sales Trend Line Chart


---

# 📁 Project Files

- Dataset for Data Analytics(1).xlsx
- Cleaned_Dataset2.xlsx
- README.md




---

# 👩‍💻 Author

**Prensi Saxena**

BCA Student

---

# ⭐ Conclusion

This project helped in understanding real-world E-Commerce data analysis workflow including data cleaning, exploratory analysis, visualization, and extracting meaningful business insights using Excel.
