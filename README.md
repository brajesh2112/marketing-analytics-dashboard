# 📊 Marketing Analytics Dashboard

An interactive Streamlit dashboard that helps businesses explore **customer segmentation**, **lifetime value estimation**, **market basket analysis**, and **A/B testing simulations** using machine learning techniques. This project demonstrates how marketing insights can be derived from customer data to boost retention, upsell opportunities, and campaign performance.

---

## 📈 Key Features

### 1. 🛒 **Customer Lifetime Value (CLV) Prediction**
- Predict CLV using tenure and monthly charges
- Simulate new customer CLV via sidebar inputs

### 2. 🎯 **Customer Segmentation**
- KMeans clustering based on customer spending behavior
- Segments: Low Spend, Medium Spend, High Spend
- Pie chart visualization with tailored marketing strategies

### 3. 🔗 **Market Basket Analysis**
- Frequent itemset mining with the Apriori algorithm
- Generate association rules to uncover cross-sell and upsell opportunities
- Example: If a user has StreamingTV, suggest StreamingMovies

### 4. 🧪 **A/B Testing Simulator**
- Compare conversion outcomes between two marketing strategies:
  - Discount Offer
  - Premium Support
- Visualize which strategy performs better using simulated data

---

## 📊 Dataset Used

- **Dataset Name**: Churn_pred.csv
- **Origin**: Based on telecom customer behavior
- **Example Source**: [Kaggle - Website Traffic Dataset](https://www.kaggle.com/datasets/rashadrmammadov/customer-churn-dataset)

---

## 🚀 How to Run

### Prerequisites:
Install required packages:
```bash
pip install streamlit pandas numpy matplotlib seaborn scikit-learn mlxtend
