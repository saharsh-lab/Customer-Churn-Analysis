# 📊 Telecom Customer Churn Analysis

This project focuses on analyzing and predicting customer churn in a telecom company. Churn refers to when a customer discontinues their service. Understanding churn helps businesses retain valuable customers and improve overall service.

---

## 📌 Objective

The primary goal of this project is to:
- Analyze patterns that lead to customer churn.
- Visualize the key factors influencing churn.
- Build a predictive model to estimate the likelihood of churn for each customer.
- Provide actionable insights and recommendations based on data analysis.

---

## 📁 Dataset

The dataset contains various features including:
- **Demographic data:** gender, senior citizen, partner, dependents.
- **Service data:** phone service, internet service, streaming TV, etc.
- **Account data:** contract type, payment method, monthly charges, tenure.
- **Target variable:** Churn (Yes/No)

---

## 🚀 Features Implemented

### 🔍 1. Data Cleaning & Preprocessing
- Handling missing values and data formatting.
- Converting categorical variables into numeric using encoding techniques.

### 📊 2. Exploratory Data Analysis (EDA)
- Visual analysis using pie charts, bar plots, and heatmaps.
- Distribution of churn based on features like tenure, contract type, payment method.

### 📉 3. Model Building & Evaluation
- Used **Logistic Regression** to classify churn.
- Trained on 80% of the data, tested on 20%.
- Evaluated using accuracy, confusion matrix, and classification report.

### 📈 4. Visualizations
- Churn distribution pie chart.
- Tenure vs Churn bar plot.
- Heatmap showing feature correlations.

### 📤 5. Final Output
- Created a CSV (`LTV_predictions.csv`) containing customer churn probabilities.

---

## 🧰 Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- sql
