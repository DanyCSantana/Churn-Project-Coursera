# Telecom Churn Analysis Project

## 📊 Overview

This project performs churn analysis in the telecom industry using Python. Based on a public dataset from Kaggle, the analysis explores patterns in customer cancellations and highlights key churn drivers using data visualization and exploratory data analysis techniques. The goal is to help telecom companies understand churn behaviour and develop strategies to improve customer retention.

GitHub Repository: [UCDPA_DANYELLASANTANA](https://github.com/DanyCSantana/UCDPA_DANYELLASANTANA)

---

## 🧠 Abstract

The dataset includes customer demographics, service usage patterns, and customer service call records. Python libraries such as `pandas`, `matplotlib`, and `seaborn` were used for data preprocessing, transformation, and visualization.

The analysis investigates:
- Overall churn rate
- Churn by US region
- Relationship between customer service calls and churn
- Impact of account length on customer churn

---

## 🔧 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
  
---

## 📁 Dataset

- **Primary Source:** Kaggle Telecom Churn Dataset  
  [https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets)

- **Secondary Source:** State name and abbreviation data from Statistics Canada  
  [https://www23.statcan.gc.ca/imdb/p3VD.pl?Function=getVD&TVD=53971](https://www23.statcan.gc.ca/imdb/p3VD.pl?Function=getVD&TVD=53971)

---

## ⚙️ Implementation Steps

1. **Data Import & Cleaning:**
   - Load datasets using `pandas`
   - Inspect structure with `.head()` and `.describe()`
   - Handle missing values and duplicate columns

2. **Data Enrichment:**
   - Add US state names via external source
   - Merge region dictionary to analyse churn by region

3. **Exploratory Data Analysis (EDA):**
   - Churn count & percentage
   - Churn by region
   - Call activity and churn correlation
   - Account length grouping with a custom function

4. **Visualization:**
   - Bar plots, pie charts, and grouped charts with `matplotlib` and `seaborn`

---

## 📈 Key Findings

- **Churn Rate:** 14.5% of customers have cancelled their service.
- **Highest Churn by Region:** Northeast (16.9%)
- **Customer Service Influence:** 81% of churned customers contacted customer service at least once.
- **Account Length Risk Zone:** Customers with 6–10 years of service are the most likely to churn.

---

## 🧩 Insights & Recommendations

- **Retention Focus:** The company should focus on medium-term customers (6–11 years).
- **Improve Support:** Enhance customer service quality to prevent escalation into cancellations.
- **Regional Strategy:** Investigate why Northeast states show higher churn for tailored retention campaigns.
- **Monitor Loyalty:** Review existing loyalty initiatives for effectiveness and consider early warning systems for potential churners.

---

## 📌 About the Author

This project was developed by **Danyella Santana**, based on her professional experience as a Marketing Analyst in the telecom sector. The analysis reflects both data-driven insights and real-world understanding of churn dynamics in subscription-based services.




