# 📊 Food Order Costs vs Profit Analytics

### 🔍 An in-depth analysis of food delivery order economics using Python & real-world data

---

## 📁 Project Overview

This project investigates how various components of food delivery orders — such as order value, discounts, delivery fees, and platform commissions — influence **net revenue** and **profitability**. Using a sample dataset from food orders in New Delhi, the goal is to:

- Engineer insightful metrics like **net revenue** and **profit**
- Visualize patterns in customer spend and discounts
- Identify **key drivers of profit**
- Provide **data-backed recommendations** for margin optimization

---

## 🧠 Key Objectives

- Understand the **cost structure** of food delivery platforms
- Analyze the **impact of discounts** on profit margins
- Identify trends in **payment methods** and **order patterns**
- Build a reproducible data analysis pipeline using Python

---

## 📊 Features & Analysis

| Analysis Component        | Description |
|---------------------------|-------------|
| 🔄 Data Cleaning          | Parsing discounts, date formatting, handling nulls |
| 📈 Exploratory Analysis   | Spend distribution, payment trends, top restaurants |
| 🧮 Feature Engineering    | Discount Amount, Net Revenue, Total Cost, Profit |
| 📉 Profit Modeling        | Correlation heatmaps, regression on order value |
| 📊 Visual Insights        | Seaborn & Matplotlib visualizations |
| 📑 Report Export          | `.docx` report with visual insights |
| 📦 Dashboard Ready        | Scalable for integration into Streamlit or Plotly Dash |

---

## 🧾 Sample Summary Metrics

| Metric                     | Value (Example) |
|----------------------------|-----------------|
| Total Orders               | 1,000           |
| Total Revenue              | ₹1,200,000+     |
| Total Discounts Given      | ₹80,000+        |
| Average Profit per Order   | ₹650+           |

---

# Project Features

## 🔧 Phase 1: Data Preparation & Cleaning

- Cleaned and parsed all date and discount fields  
- Converted discount strings to numeric format  
- Extracted useful features such as `Order Date`  
- Engineered financial metrics: `Net Revenue`, `Total Cost`, and `Profit`  

---

## 📊 Phase 2: Key Findings with Visual Insights

### 1. Profit Distribution  
![Spend by New Customers](https://github.com/user-attachments/assets/bede1c67-4929-4a45-8053-3d71c93d7e94) 

📌 **Key Insight:** Most orders cluster around moderate profit ranges. Outliers exist due to extreme refunds or very high-value orders.  

---

### 2. Top Restaurants by Order Volume  
![Top10 Restaurants by number](https://github.com/user-attachments/assets/1aaaea41-1f07-4087-beec-8f4483465094)

📌 **Key Insight:** A small group of restaurants accounts for a large share of total orders.  

---

### 3. Payment Method Distribution  
![Payment Method Distribution](https://github.com/user-attachments/assets/ea925d81-979f-4b16-8984-8cbc9ceee5b6)

📌 **Key Insight:** Digital payments dominate, suggesting user trust in cashless options.  

---

### 4. Orders Over Time  
![Order Trend Over Time](https://github.com/user-attachments/assets/f80978d7-b81c-475f-85bf-4dca832cc61d)

📌 **Key Insight:** Peak activity observed on weekends and around dinner times.  

---

### 5.  Profit after Discount 
![Effect of discount on Profit](https://github.com/user-attachments/assets/9886305d-a616-4b97-abfe-a9a3fe6fb01d) 

📌 **Key Insight:** Higher discounts often correlate with lower profit margins.  

---

### 6. Correlation Matrix of Features  
![Heatmap](https://github.com/user-attachments/assets/b02d4a55-7fc4-424c-a096-175ce5c466a4) 

📌 **Key Insight:** Strong positive correlation between order value and profit; discount amount shows negative correlation with profit.  

---

## 📈 Phase 3: Insights & Interpretation

- **Order Value** is the strongest predictor of **Profit**  
- Discounts have a diminishing return beyond a certain threshold  
- Balanced delivery fees can raise **net revenue**  
- Digital wallets and credit cards are efficient and preferred by users  


---

## 🛠 Tech Stack

- **Python 3.9+**
- `pandas`, `numpy` – Data wrangling  
- `matplotlib`, `seaborn` – Visualizations  
- `sklearn` – Modeling & regression    
- `Jupyter Notebook` – Interactive analysis

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/MrigenDeka04/Food_order_costs_vs_profit_analytics.git
   cd Food_order_costs_vs_profit_analytics
   ```

---

## 📈 Future Improvements

- Add customer segmentation (e.g., new vs returning users)
- Build a dashboard using **Streamlit** or **Plotly Dash**
- Integrate profit forecasting models
- Expand dataset to include multi-city or multi-country data

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- Real-world-style dataset for simulation
- Open-source Python ecosystem
- Inspired by real food delivery business models


                                                                        
