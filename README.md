📊Amazon Sales Data Analysis (EDA Project)
📌Project Overview

This project performs Exploratory Data Analysis (EDA) on an Amazon sales dataset using Python.
The goal is to analyze sales performance, customer behavior, product performance, pricing strategy,
and revenue trends using statistical analysis and visualizations.

The dataset contains 50,000 sales transactions across multiple product categories, regions, and payment methods.

📁Dataset Description

The dataset contains the following features:

Column Name	Description
order_id	Unique order identifier
order_date	Date of order
product_id	Unique product identifier
product_category	Category of product
price	Original product price
discount_percent	Discount applied
quantity_sold	Units sold
customer_region	Customer location
payment_method	Payment type used
rating	Product rating
review_count	Number of reviews
discounted_price	Price after discount
total_revenue	Revenue generated
🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🔎 Data Cleaning & Preprocessing
✔ Data Type Conversion

Converted order_date from object to datetime format.

✔ Data Validation

Verified dataset contains no missing values.

Checked for duplicate records.

✔ Pricing Validation

Verified discounted prices using formula:

price * (1 - discount_percent / 100)

✔ Feature Engineering

## ⚙ Feature Engineering

Created new analytical columns:

- `year`
- `month`
- `month_name`
- `week`
- `discount_group`
- `price_group`
- `review_group`

---

## 📊 Exploratory Data Analysis

---

### 🛍 Revenue Analysis

#### Revenue by Product Category
- Revenue contribution is evenly distributed across categories.
- Home & Kitchen shows slightly higher average revenue.

#### Revenue by Region
- Sales performance is consistent across all regions.

#### Revenue by Payment Method
- Wallet and UPI payments generated slightly higher revenue.
- All payment methods contribute almost equally.

---

### 📦 Product Sales Analysis

#### Products Sold by Category
- Beauty category recorded highest product sales.
- Home & Kitchen category recorded lowest product sales.

#### Products Sold by Region
- Sales distribution remains balanced across regions.

---

### ⭐ Customer Behavior Analysis

#### Average Rating by Category
- Ratings remain stable across product categories.
- Books category recorded slightly higher average ratings.

#### Average Rating by Region
- Middle East recorded the highest average customer rating.

---

### 💰 Pricing & Discount Insights

#### Discount Segmentation
Discounts categorized into:
- Low (0–10%)
- Medium (10–20%)
- High (20–30%)

#### Price Segmentation
Products grouped into:
- Low
- Affordable
- High
- Premium

#### Review Segmentation
Customer ratings categorized into:
- Low
- Average
- High

---

### Correlation Analysis

Generated correlation heatmap to analyze relationships between:

- Price
- Discount Percent
- Quantity Sold
- Rating
- Review Count
- Total Revenue

---

### Time Series Analysis

#### Yearly Revenue
- Revenue remained stable across 2022 and 2023.

#### Monthly Sales Trends
- Sales remained consistent across months.
- Slight peak observed during early and mid-year months.

#### Orders by Weekday
- Orders are evenly distributed across weekdays.

---

### Rating vs Revenue Analysis

| Rating Group | Revenue Trend |
|-------------|-------------|
| Average | Highest revenue |
| Low | Moderate revenue |
| High | Slightly lower revenue |

---

## 📈 Visualizations

- Revenue distribution pie charts
- Category sales comparison
- Region-wise sales visualization
- Payment method revenue bar chart
- Correlation heatmap
- Monthly and yearly revenue trends

---

## Key Business Insights

- Product categories contribute evenly to total revenue.
- Discount strategies show minimal variation in sales performance.
- Customer ratings remain stable across products and regions.
- Revenue trends show consistency across years.
- Flexible payment methods help maintain steady sales.
- Regional purchasing patterns remain balanced.

---

📎 Project Structure
├── amazon_sales_dataset.csv
├── Amazon_Sales_EDA.ipynb
├── README.md

Author

AB
Aspiring Data Analyst
