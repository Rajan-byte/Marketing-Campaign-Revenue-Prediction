End-to-end data science project analyzing marketing campaign performance, cleaning real-world data, performing EDA, and building machine learning models to predict revenue.

## Marketing Campaign Revenue Prediction
## 📌 Project Overview
This project analyzes real-world marketing campaign data to understand key drivers of revenue and build a machine learning model to predict campaign revenue. The dataset contains missing values, inconsistent records, and requires significant preprocessing.

## 🎯 Business Objective
- Identify high-performing marketing channels
- Understand what factors drive revenue
- Predict revenue for future campaigns
- Provide actionable insights for budget optimization

## 🧰 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Key Steps
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA)
- Feature engineering (CTR, ROI, conversion rate)
- Machine learning pipelines
- Model comparison and evaluation

## 🤖 Models Used
- Linear Regression (Baseline)
- Random Forest Regressor (Final Model)

## 📊 Results
- Random Forest achieved significantly lower RMSE and MAE compared to baseline
- Key revenue drivers identified: spend, clicks, impressions, region, and channel
- Model limitations identified for low-spend and poor-quality campaigns

## ⚠️ ERROR ANALYSIS — MODEL LIMITATIONS
Channel	             Avg Error
Email (Low spend) 	 $2,512
Facebook (Med-High)	 $1,588

Q. What This Means ?
- Low-spend & data-quality issues (impressions = 0)

## Unstable performance for:
- Email promos
- Campaigns with tracking gaps

## 📌 Action:
- Improve tracking for Email campaigns
- Avoid predictions when impressions = 0

## 💼 Business Insights
- Google and Email campaigns generate the highest ROI
- Engagement (clicks) is more important than reach (impressions)
- Influencer campaigns consistently underperform
- Regional performance varies significantly

## 🚀 Future Work
- Add more campaign data
- Deploy model as an API
- Build Power BI / Tableau dashboards

---
