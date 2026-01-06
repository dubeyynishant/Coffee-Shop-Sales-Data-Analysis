# ☕ Coffee Shop Sales Data Analysis

A comprehensive **Coffee Shop Sales Analysis** project featuring Exploratory Data Analysis (EDA) and an interactive **Streamlit Dashboard** built with Python — powered by Pandas and Plotly — to analyze 6-month sales data and uncover business insights.

![Dashboard Preview](https://github.com/dubeyynishant/Coffee-Shop-Sales-Data-Analysis/blob/main/Dashboard_Image.png)

---

## 📌 Overview

This project analyzes coffee shop sales data to understand:

💡 revenue trends
📍 store performance
☕ popular products & categories
📆 peak hours and days
📊 customer preferences

It includes **data cleaning & visualization**, **insight extraction**, and a **professional dashboard** that makes insights easy to explore and interpret.

---

## 🗂 Repository Structure

```
Coffee-Shop-Sales-Data-Analysis/
├── EDA.ipynb                      # Exploration and insights with plots
├── Dashboard.py                  # Streamlit dashboard file
├── cleaned_coffee_sales_dataset.csv   # Main dataset
├── Dashboard_Image.png         # Dashboard preview image
├── requirements.txt              # Project dependencies
└── README.md                     # This file
```

---

## 📈 Dataset

The dataset (`cleaned_coffee_sales_dataset.csv`) contains **149,116 transaction records** including:

* Transaction ID
* Transaction Date & Time
* Store Location
* Product
* Product Category
* Sales Amount
* Month / Weekday / Hour

These features fuel trend analysis and KPI visualization.

---

## 🧠 Exploratory Data Analysis (EDA)

The **EDA notebook (EDA.ipynb)** performs:

✔ Data cleaning and preprocessing
✔ Revenue trend analysis
✔ Order patterns by weekday and hour
✔ Top selling products and categories
✔ Store performance comparison

Key observations include:

* Sales increased steadily throughout the 6 months
* Certain products drove most of the revenue
* Customer activity peaks during specific hours
* Category preferences vary widely

---

## 📊 Interactive Streamlit Dashboard

The dashboard provides a real-time, interactive view of your sales data with:

### 🔹 KPI Metrics

* Total Revenue
* Total Orders
* Average Order Value (AOV)
* Peak Sales Location

### 🔹 Visual Insights

* Monthly Sales Trend
* Sales by Location (donut chart)
* Top 10 Products by Revenue
* Average Order Value by Category
* Popular Categories
* Peak Hour & Peak Day
* Coffee Type Order Distribution

All visuals are built using **Plotly Express** for responsiveness and clarity.

---

## 🚀 How to Run

### 1. Clone the repo

```bash
git clone https://github.com/dubeyynishant/Coffee-Shop-Sales-Data-Analysis.git
cd Coffee-Shop-Sales-Data-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the dashboard

```bash
streamlit run Dashboard.py
```

The dashboard opens automatically at:

```
http://localhost:8501
```

---

## 🛠 Tools & Libraries Used

| Category        | Tools            |
| --------------- | ---------------- |
| Data Processing | Pandas           |
| Visualization   | Plotly, Altair   |
| Dashboard       | Streamlit        |
| Notebook        | Jupyter Notebook |
| Python          | Python 3.8+      |

---

## 💡 Key Insights

* **Total Revenue:** ~$698,000
* **Total Orders:** ~149,000
* **Top Store:** Hell’s Kitchen
* **Most Profitable Products:** (e.g., Barista Espresso)
* **Most Popular Category:** Coffee
* **Peak Hour:** Around 10 AM
* **Steady Sales Across Weekdays**

*(Actual numbers will vary based on dataset values.)*

---

## 📁 Further Enhancements

You can extend this project by adding:

✔ Time-based filters in the dashboard
✔ Forecasting using machine learning
✔ Real-time data integration
✔ Export to PDF/Image
✔ User authentication

---

## 👤 Author

**Nishant Dubey**

Data Analyst | Python | Visualization Enthusiast
🔗 [https://github.com/dubeyynishant](https://github.com/dubeyynishant)

---

⭐ *If you find this project helpful, please give it a star!*

