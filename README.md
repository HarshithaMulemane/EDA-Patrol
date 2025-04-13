# 📊 Crime Pattern Analysis in India: A Data-Driven Approach

## 💡 Project Overview
This project investigates district-wise crime data across India (2001–2014) using data science and machine learning techniques. The goal is to uncover crime patterns, identify high-risk zones, forecast crime trends, and support data-informed decisions for public safety and policy-making.

---

## 🛡️ Objectives

- Analyze total and type-wise IPC crimes across districts and states
- Identify seasonal and regional crime trends
- Cluster districts based on crime behavior using K-Means
- Predict crime trends using regression models
- Classify high vs. low crime districts using machine learning
- Develop a Crime Risk Index for ranking high-risk areas
- Deep dive into crimes against women, dowry deaths, and city-specific impacts

---

## 🔄 Data Preparation

- **Dataset**: District-wise Crime in India (2001–2014) from [data.gov.in](https://data.gov.in)
- Standardized column names and handled missing values
- Removed aggregate rows (e.g., "Total")
- Converted columns to appropriate data types

---

## 📊 Exploratory Data Analysis

### 🧮 Crime Volumes
- Total IPC crimes recorded: **29 million+**
- Avg. murders per district-year: ~46

### 📍 Regional Insights
- **Top Crime States**: Maharashtra, Uttar Pradesh, Kerala
- **Top Crime Districts**: Mumbai, Delhi, Ernakulam
- **Lowest Crime State**: *[Calculated based on IPC total]*

### 📈 Correlations
- Strong positive correlation between **murders**, **thefts**, and **total IPC crimes**

---

## 📝 Advanced Analysis

### ✅ Most Common Crimes
Identified most frequent crime type per district

### ✅ K-Means Clustering
Clustered districts into 4 segments based on crime profiles

### ✅ Regression Forecasting
Predicted future IPC crimes in Mumbai using **Linear Regression**  
Projected crime trends until **2025**

### ✅ Classification
Used **Random Forest Classifier** to label districts as:
- "High Crime"
- "Low Crime"

### ✅ Crime Risk Index
Created a normalized **Crime Risk Score** (0–1) to rank districts

---

## 📅 Bonus Insights

- **Crimes Against Women**: % of IPC crimes committed against women calculated
- **Dowry Deaths**: Highest reporting state identified
- **Seasonal Trends**: Simulated monthly trends due to lack of month-wise data
- **Cities vs Crime Rates**: Metro cities like Mumbai, Delhi show significantly higher IPC counts

---

## 📈 Visualizations

- 📍 Top 10 crime-prone districts (bar chart)
- 📊 Crime distribution by state
- 🔥 Heatmaps of violent crime correlations
- 🗓️ Simulated monthly crime trends
- 🧩 K-Means clustering scatter plot
- ⚠️ Crime Risk Index bar graph
- 📉 Forecasted crime trend line charts

---

## 🎓 Key Learnings

- Real-world data is messy; data cleaning is crucial
- Domain context enhances feature selection and interpretation
- Visual storytelling is powerful for public and policy impact
- Combining ML with EDA delivers rich, actionable insights

---

## 🚀 Future Work

- Integrate population & socioeconomic indicators
- Apply true geospatial analysis (GeoPandas, Folium)
- Deploy on **Streamlit** as a public dashboard
- Use advanced time series models (ARIMA, LSTM) for better accuracy

---

## 💡 Built With

- **Python** (Pandas, NumPy, Scikit-learn)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Modeling**: Statsmodels, Sklearn
- **Tools**: Jupyter Notebook, Google Colab

---

## 🌟 Contribution

Led end-to-end development:
- 📥 Data cleaning & transformation  
- 📊 EDA & Visualization  
- 🔍 Modeling (Clustering, Regression, Classification)  
- 📈 Reporting & Insight generation

---

## 🎡 Tagline

> **"From chaos to clarity: decoding India’s crime data with code."**

---

## 📁 Repository Structure (Optional)

