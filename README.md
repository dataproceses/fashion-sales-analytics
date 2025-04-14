# 🛍️ Fashion Retail Analysis

## 📊 Overview

This project explores and analyzes customer behavior, sales trends, and product performance in a fashion retail dataset. By leveraging data analysis techniques and visualizations, the objective is to uncover key business insights, identify customer segments, and evaluate product ratings and purchasing patterns over time.

---

## 🎯 Objectives

- Analyze **purchase trends** across time (yearly, monthly, weekly).
- Segment customers based on **spending behavior** and **purchase frequency**.
- Evaluate **product performance** through sales and customer reviews.
- Detect **seasonal patterns** and **peak sales periods**.
- Visualize key insights using **Seaborn** and **Matplotlib**.

---

## 🧩 Dataset Structure

The dataset contains the following columns:

| Column Name               | Description                                   |
|--------------------------|-----------------------------------------------|
| `Customer Reference ID`  | Unique identifier for each customer           |
| `Item Purchased`         | Product or item purchased                     |
| `Purchase Amount (USD)`  | Total purchase amount in USD                  |
| `Date Purchase`          | Date of transaction                           |
| `Review Rating`          | Customer's product review rating              |
| `Payment Method`         | Payment type used (e.g., Credit Card, PayPal) |
| `Year`                   | Year of purchase                              |
| `Month`                  | Month of purchase                             |
| `Weak Day`               | Day of the week (e.g., Monday, Friday)        |

---

## 🧪 Key Analyses Performed

- **Descriptive Analysis**: Summary statistics of purchase amounts and ratings.
- **Customer Segmentation**:
  - **VIP**: High spenders with frequent purchases.
  - **Ordinary**: Moderate spenders with consistent activity.
  - **New**: Recently joined or low activity customers.
- **Sales Trend Analysis**: 
  - Yearly, monthly, and weekday sales patterns.
  - Cumulative (YTD) sales, orders, and quantity sold.
- **Product Segmentation**:
  - Total and average purchase value by product.
  - Review rating distributions by product.
- **Visualizations**:
  - Lineplot, Histograms, boxplots, pie charts, heatmaps, and bar plots for deeper insights.

---

## 📌 Tools & Libraries Used

- **Python 3.12**
- **Pandas** – data manipulation and aggregation
- **Matplotlib / Seaborn** – data visualization
- **Jupyter Notebook** – for analysis and presentation

---

## 📈 Key Insights

- **Majority of purchases** were concentrated among a small group of **VIP customers**.
- **Certain products** received consistently higher ratings and sales volume.
- **Monthly trends** revealed peak purchasing periods (e.g., holiday seasons).
- **Most customers gave 3-star ratings**, indicating overall satisfaction.
- **Outliers** in purchase amounts were detected using boxplots.

---

## ✅ Future Improvements

- Incorporate **customer demographic data** for more refined segmentation.
- Apply **predictive modeling** for customer churn or future purchases.
- Introduce **RFM analysis** or **clustering algorithms** (e.g., K-Means).
- Create an interactive dashboard using **Plotly** or **Power BI**.



