# Amazon Sales Data Analysis 📦📊

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on an Amazon sales dataset to understand sales performance, customer behavior, pricing patterns, and revenue trends across products, regions, and time.

Python was used for **data cleaning, transformation, feature engineering, and visualization** to derive meaningful business insights from raw transactional data.

---

## 🗂 Dataset Description
- **File Name:** `amazon_sales_dataset.csv`
- **Total Records:** 50,000
- **Total Columns:** 13 (initial)

### Key Columns
- Order details: `order_id`, `order_date`, `product_id`
- Product details: `product_category`, `price`, `discount_percent`
- Sales metrics: `quantity_sold`, `discounted_price`, `total_revenue`
- Customer attributes: `customer_region`, `payment_method`
- Feedback metrics: `rating`, `review_count`

---

## 🧰 Tools & Libraries
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## 🧹 Data Cleaning & Preparation
The following preprocessing steps were performed:

- Loaded the dataset using Pandas
- Converted `order_date` from object to datetime format
- Verified data types of all columns
- Checked and confirmed:
  - No missing values
  - No duplicate records
- Validated discounted price calculations using the discount percentage

---

## ⚙️ Feature Engineering
New features were created to support deeper analysis:

- **Time-based features**
  - `year`
  - `month`
  - `month_name`
  - `week` (day of week)
- **Discount Buckets**
  - Low, Medium, High (based on discount percentage)
- **Price Segments**
  - Low, Affordable, High, Premium (quartile-based)
- **Review Groups**
  - Low, Average, High (rating-based quantiles)

These features enabled better segmentation of revenue and customer behavior.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Product & Category Analysis
- Average revenue by product category
- Total revenue contribution by category (pie chart)
- Total products sold by category

### 🔹 Regional Analysis
- Revenue distribution by customer region
- Quantity of products sold by region
- Average customer ratings by region

### 🔹 Payment Method Analysis
- Total and average revenue by payment method
- Comparison of revenue contribution across payment types

### 🔹 Time-Based Analysis
- Year-wise revenue comparison (2022 vs 2023)
- Monthly revenue trends for each year
- Order distribution across weekdays

### 🔹 Customer Feedback Analysis
- Average rating by product category
- Revenue contribution based on review groups
- Relationship between ratings and revenue

### 🔹 Correlation Analysis
- Heatmap showing correlation between:
  - Price
  - Discount percentage
  - Quantity sold
  - Ratings
  - Review count
  - Total revenue

---

## 📈 Key Insights
- Revenue is evenly distributed across major product categories
- Wallet and Credit Card payments generate the highest revenue
- Middle East and North America show slightly higher average ratings
- Year 2023 shows marginal revenue growth compared to 2022
- Medium discount levels are most common across transactions
- Products with average ratings contribute the highest total revenue
- Quantity sold has a stronger impact on revenue than ratings

---

## 📂 Repository Contents
- `eda-amazon_sales.ipynb` – Jupyter Notebook with full analysis
- `amazon_sales_dataset.csv` – Raw dataset
- `visualizations/` – Generated plots and charts (if saved)
- `README.md` – Project documentation

---

## 👤 Author
**AB**  
Aspiring Data Analyst  
