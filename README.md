# E-commerce-analysis
# 🛍️ Order Return Prediction – eCommerce Analytics Project

This project focuses on analyzing eCommerce transaction data to uncover business insights and build a machine learning model that predicts whether an order will be returned. It includes complete end-to-end data cleaning, exploratory analysis, modeling, and deployment through a Streamlit app.
This project focuses on analyzing and improving customer retention and operational efficiency by predicting order returns in an eCommerce setting. The dataset used includes over 3,000 transaction records, with features like product category, payment method, region, quantity, and price.

## 🔍 Key Features

- Data Cleaning using Pandas & Power Query
- Exploratory Data Analysis (EDA) for sales, products, and customers
- Customer Segmentation by spending behavior
- Predictive modeling using Random Forest (90%+ accuracy)
- Deployment of return prediction model with Streamlit
- Feature Importance Visualization and Business Recommendations

## 🧰 Tech Stack

- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- Streamlit (Web App Deployment)
- Joblib (Model Serialization)
- Excel / Power Query (Initial Cleaning)

## 📁 Project Structure

### 🧹 Phase 1: Data Cleaning & EDA

- Cleaned data using Excel, Power Query, and Python (Pandas)
- Converted date formats, handled outliers, and standardized categories
- Conducted exploratory analysis of:
  - Monthly revenue trends
  - Top-performing product categories
  - Sales performance by customer region
  - Customer segmentation based on spending behavior

---

### 🤖 Phase 2: Modeling

- Labeled the 'Returned' column for binary classification
- One-hot encoded categorical variables
- Trained a Random Forest Classifier on transaction data
- Achieved over 90% accuracy in predicting order returns
- Analyzed feature importance for actionable business insights

---

### 🖥️ Phase 3: App Development

- Built a user-friendly Streamlit app that accepts order details as input
- Deployed the trained model to predict return likelihood
- Allows for real-time decision support in customer service or logistics teams

---

### 📊 Key Deliverables

- Power BI / Excel Dashboard
- Python EDA Notebook
- Trained Machine Learning Model (.pkl)
- Streamlit Web App (`app.py`)
---

### 💡 Business Impact

- Improves return management by flagging high-risk orders
- Supports marketing teams with customer segmentation
- Helps inventory and logistics teams prioritize high-value regions and categories

