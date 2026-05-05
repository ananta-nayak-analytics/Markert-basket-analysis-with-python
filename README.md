# 🛒 Market Basket Analysis with Python

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-orange)
![Machine Learning](https://img.shields.io/badge/ML-KMeans-green)

## 📌 Project Overview
This project analyzes customer shopping behavior using data cleaning, exploratory data analysis (EDA), and clustering techniques. It aims to identify purchasing patterns, customer satisfaction trends, and recommendation effectiveness to generate actionable business insights.

## 🎯 Business Objectives
* Understand customer purchase behavior
* Identify factors affecting customer satisfaction
* Segment customers based on behavior
* Improve recommendation strategies

## 🧾 Dataset Description
The dataset includes:
* Customer demographics (Age, Gender)
* Purchase frequency
* Product categories
* Shopping satisfaction
* Recommendation helpfulness
* Cart abandonment reasons

## ⚙️ Tech Stack
* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (K-Means Clustering)
* Jupyter Notebook

## 🔍 Methodology
### 1. Data Cleaning
* Removed duplicates
* Handled missing values
* Encoded categorical variables

### 2. Exploratory Data Analysis (EDA)
* Analyzed customer demographics
* Studied purchase trends
* Evaluated satisfaction levels
* Identified key behavioral patterns

### 3. Customer Segmentation
* Applied K-Means clustering
* Segmented customers based on purchase frequency and satisfaction
* Evaluated clusters using Elbow Method

## 📊 Key Findings & Insights
### 🧠 Customer Behavior
* Majority of customers are **occasional shoppers**
* Customer satisfaction is **moderate**, indicating improvement scope
### 📈 Relationships
* Strong positive relationship between:

  * Recommendation helpfulness
  * Customer satisfaction
    👉 Better recommendations lead to better experience
### 🛍️ Purchase Patterns
* Certain product categories dominate purchases
* Customers prefer specific browsing/search methods
### ⚠️ Cart Abandonment
* Main reasons:
  * High pricing
  * Additional costs (shipping, etc.)
### 👥 Customer Segments
* **Frequent Buyers** → High-value customers
* **Occasional Shoppers** → Growth opportunity
* **At-Risk Customers** → Require retention strategies

## 💡 Business Recommendations

* Improve recommendation systems using personalization
* Target at-risk customers with offers
* Enhance loyalty programs for frequent buyers
* Optimize pricing and reduce hidden costs
* Improve user experience to reduce cart abandonment

## 📊 Visualizations

### Distribution Plot

![Distribution](images/Screenshot 2026-05-05 185426.png)

### Correlation Heatmap

![Heatmap](images/Screenshot 2026-05-05 185438.png)

### Customer Segmentation

![Cluster](images/Screenshot 2026-05-05 190015.png)

## 🚀 How to Run
```bash
git clone https://github.com/ananta-nayak-analytics/market-basket-analysis-with-python.git
cd market-basket-analysis-with-python
pip install -r requirements.txt
jupyter notebook
```
## 📂 Project Structure
```
market-basket-analysis/
│── images/
│── notebook.ipynb
│── README.md
│── requirements.txt
```
## 🌟 Future Improvements
* Implement Association Rule Mining (Apriori)
* Build recommendation system
* Deploy dashboard using Streamlit or Power BI

## 📜 License
MIT License

## 👤 Author
**Ananta Nayak**
Aspiring Data Analyst | Python | SQL | Power BI|ML

