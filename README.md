📊 Crime Pattern Analysis in India: A Data-Driven Approach
💡 Project Overview
This project investigates district-wise crime data across India from 2001 to 2014 using data science and machine learning techniques. The goal is to uncover crime patterns, identify high-risk zones, forecast future crime trends, and support data-informed decision-making for public safety.

🛡️ Objectives
Analyze total and type-wise IPC crimes across districts and states
Identify seasonal and regional crime trends
Cluster districts by crime behavior using K-Means
Predict crime trends using regression
Classify high vs. low crime districts using ML
Develop a Crime Risk Index
Examine crimes against women, dowry deaths, and city-specific crime impact
🔄 Data Preparation
Dataset: District-wise Crime in India (2001–2014)
Columns standardized, missing values handled, data types converted
Removed aggregate rows ("Total", etc.)
📊 Exploratory Data Analysis
Total Crimes & Murders
Total IPC crimes recorded: 29M+
Average murders per district-year entry: ~46
State & District Insights
Top Crime States: Maharashtra, Uttar Pradesh, Kerala
Top Crime Districts: Mumbai, Delhi, Ernakulam
Lowest Crime State: [Calculated using total IPC crimes sum]
Correlations
Positive correlation found between murders, thefts, and total IPC crimes
📝 Advanced Analysis
✅ Most Common Crimes
For each district, the most frequently reported crime type was identified
✅ K-Means Clustering
Grouped districts into 4 clusters based on similar crime patterns
Useful for profiling high- and low-intensity crime zones
✅ Regression Forecasting
Predicted future IPC crimes in Mumbai using Linear Regression
Projected crime trends until 2025
✅ Classification
Built Random Forest Classifier to label districts as "High Crime" or "Low Crime"
Based on total IPC crimes and other crime features
✅ Crime Risk Index
Developed normalized score (0–1) to quantify risk level of each district
Used for ranking high-risk areas
📅 Bonus Insights
✅ Crimes Against Women
% of IPC crimes committed against women: [Calculated based on relevant categories]
✅ Dowry Deaths
State with highest dowry deaths: [Identified using grouped totals]
✅ Seasonal Trends (Simulated)
Lacking month data, simulated monthly crime distribution from annual trends
Showed consistent distribution across months (for visualization only)
✅ Cities vs Crime Rates
Major cities (Mumbai, Delhi, Bangalore, etc.) showed significantly higher IPC crime totals compared to other districts
📈 Visualizations
Top 10 crime-prone districts
Crime distribution by state
Heatmaps for violent crime correlation
Simulated monthly crime trends
Clustering scatter plots
Crime risk index bar charts
Forecast line graphs
🎓 Key Learnings
Real-world data is messy: cleaning and standardization are critical
Domain understanding improves feature engineering
Visualization bridges the gap between data and decision-making
🚀 Future Work
Integrate population/socioeconomic data for deeper analysis
Add true seasonal and geospatial mapping (using GeoPandas/Folium)
Deploy Streamlit dashboard for public and policy-level access
Enhance time series models with ARIMA/LSTM for higher accuracy
💡 Built With
Python (Pandas, NumPy, Scikit-learn)
Matplotlib, Seaborn, Plotly
Statsmodels (for time series)
Google Colab / Jupyter Notebook
🌟 Contribution
Led the full lifecycle from data preprocessing, exploration, modeling, and visualization to interpretation and documentation.

🎡 Tagline
"From chaos to clarity: decoding India’s crime data with code."
