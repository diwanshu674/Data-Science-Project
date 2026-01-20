# Data-Science-Project
# Amazon Sales Data Analysis & Order Status Prediction

This project focuses on analyzing Amazon sales data using Python and building a machine learning model to predict order status based on transaction and product features.

---

## 📌 Project Overview
The goal of this project is to:
- Perform Exploratory Data Analysis (EDA) on Amazon sales data
- Extract insights related to sales, brands, and product categories
- Build a machine learning model to predict order status
- Identify the most important factors influencing order outcomes

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset
- **File Name:** `Amazon.csv`
- The dataset contains order-level information such as:
  - Product category and brand
  - Order date
  - Quantity, price, tax, discount, shipping cost
  - Payment method
  - Order status
  - Location details (city, state, country)

---

## 🔍 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Distribution of product categories
- Sales contribution by top brands
- Order status distribution
- Correlation analysis using a heatmap
- Time-based feature extraction (Year, Month, Day)

---

## ⚙️ Data Preprocessing
- Converted `OrderDate` to datetime format
- Extracted year, month, and day features
- Handled categorical variables using Label Encoding
- Standardized numerical features using StandardScaler
- Split data into training and testing sets

---

## 🤖 Machine Learning Model
- **Algorithm:** Random Forest Classifier
- **Target Variable:** OrderStatus
- **Evaluation Metrics:**
  - Accuracy Score
  - Classification Report
  - Confusion Matrix

---

## 📊 Feature Importance
Feature importance was extracted from the Random Forest model to understand which features have the most impact on order status prediction.

---

## 📈 Results
The model achieved a reasonable accuracy and provided meaningful insights into the key factors affecting order outcomes.

---

## 🚀 Future Improvements
- Use One-Hot Encoding instead of Label Encoding
- Perform hyperparameter tuning
- Try additional models like Logistic Regression or XGBoost
- Deploy the model using Flask or Streamlit

---

## 👤 Author
**Diwanshu Sharma**  
Aspiring Data Scientist | Machine Learning Enthusiast

