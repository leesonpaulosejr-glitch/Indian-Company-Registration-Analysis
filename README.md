# 📊 Indian Company Registration Analysis

## 📌 Project Overview

This project focuses on analyzing company registration data across India to identify **spatial (state-wise)** and **temporal (time-based)** patterns. The dataset includes information on company types, registration timelines, and capital investments, enabling a comprehensive Exploratory Data Analysis (EDA).

The analysis uncovers trends in business growth, regional concentration, and financial distribution across the Indian corporate landscape.

---

## 🎯 Key Objectives

- Analyze trends in company registrations over time (year-wise and month-wise)
- Identify top-performing states based on company registrations
- Examine the distribution of company types across India
- Study variation in capital investment across regions
- Explore relationships between company type, location, and capital
- Identify growth patterns and emerging business regions

---

## 📌 Project Statement

The objective of this project is to analyze Indian company registration data to uncover trends in business growth, regional distribution, and investment patterns. The study aims to provide insights into how company incorporations vary across states and over time.

---

## 🎯 Aim of the Project

To examine spatial and temporal patterns in company incorporations across Indian states (up to 2024), and analyze how company types and capital investments vary by region.

---

## 📂 Dataset Overview

- **Dataset Name:** Indian Company Registrations  
- **Source:** India Data Portal  
- **Format:** CSV  
- **Rows:** 1,014,639  
- **Columns:** 16  

This dataset contains detailed information about company registrations across different states and time periods in India.

---

## 🧾 Column Description

| Column Name | Description |
|------------|------------|
| id | Unique identifier |
| registration_date | Date of company registration |
| cin | Corporate Identification Number |
| state_name | State of registration |
| state_code | State code |
| roc | Registrar of Companies (jurisdiction) |
| company_name | Name of the company |
| company_status | Current status of company |
| company_type | Government / Non-Government |
| company_class | Private / Public / One-person |
| company_category | Business classification |
| act_description | Industry/business activity |
| company_address | Registered address |
| company_email | Registered email |
| authorized_capital | Maximum allowed capital |
| paidup_capital | Actual invested capital |

---

## 🔍 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Distribution of company types
- Distribution of company status
- State-wise registration distribution
- Capital distribution

### 🔹 Bivariate Analysis
- Registrations across states
- Company type across states
- Capital variation across company types
- Registration trends over time

### 🔹 Multivariate Analysis
- Interaction between state, company type, and registrations
- Trends across year, state, and registrations
- Relationship between capital, state, and company type

### 🔹 Correlation Analysis
- Relationship between authorized capital and paid-up capital

---

## 📊 Visualizations

The project includes **15+ visualizations**, such as:

- Line charts (trend analysis)
- Bar charts (state/company comparisons)
- Pie charts (distribution)
- Heatmaps (state-year trends, monthly trends)
- Scatter plots (capital relationships)
- Box plots (capital distribution)
- Bubble charts (capital vs company count)
- Tree maps (ROC regions)
- Geo maps (state-wise concentration)
- 3D plots (state-year interaction)

---

## 🔑 Key Insights

- The Indian corporate sector is **dominated by non-government (private) companies**, indicating strong entrepreneurial activity.
- Most companies are **active**, reflecting a healthy business environment, though closures indicate natural churn.
- Company registrations are **highly concentrated in Maharashtra, Delhi, and Karnataka**, highlighting regional economic hubs.
- Capital distribution is **highly skewed**, with many small firms and a few large corporations.
- Government companies generally have **higher capital investment** compared to private firms.
- A **strong positive correlation exists between authorized and paid-up capital**, indicating consistent financial structuring.
- Registrations show a **clear upward trend over time**, with fluctuations influenced by external factors.
- Seasonal patterns suggest **specific months have higher incorporation activity**.
- Regional growth is uneven, indicating **shifting economic centers across states**.
- States with more companies also attract **higher overall capital investment**.
- ROC and geographic analysis confirm **clustered business activity in key regions**.
- Company structure preferences show a strong inclination toward **private company models**.

---

## 🧾 Conclusion

This project successfully conducted an end-to-end data analysis of Indian company registration data. The findings highlight strong private sector dominance, regional concentration of business activity, and a consistent financial structure across companies.

The study reveals that economic activity is concentrated in key states, capital distribution is uneven, and company registrations are steadily increasing over time. These insights demonstrate how data analysis can uncover meaningful patterns in business growth and investment behavior.

---

## 🚀 Future Scope

- Apply machine learning models to predict company growth and investment trends  
- Perform clustering to identify similar states based on business activity  
- Use time-series forecasting (ARIMA, Prophet) for future registration trends  
- Implement anomaly detection for extreme capital values  
- Integrate additional features (industry, turnover, employees) for deeper analysis  
- Develop interactive dashboards (Power BI / Plotly Dash)  
- Combine with external economic indicators (GDP, employment)  
- Automate data pipelines for continuous monitoring  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Plotly  

---

## 📌 Author

**Nikhil Leeson**
