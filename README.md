
# Rainfall Trend Analysis (India, 1901-2015)

## 📘Overview

This project analyzes long-term rainfall data for India spanning from 1901 to 2015. The main goal is to explore, visualize, and extract meaningful trends and patterns from historical rainfall records.


## 🎯 Objectives

* **Trend Analysis:** Identify how rainfall patterns have changed over time, including any upward or downward trends.
* **Anomaly Detection:** Detect unusual rainfall events or years with significantly high or low rainfall compared to normal patterns.
* **Forecasting:** Use time series forecasting models to predict future rainfall based on historical data.
* **Clustering:** Group years with similar rainfall characteristics to identify distinct climatic phases or regions.
* **Correlation Analysis:** Explore relationships between rainfall and other potential factors or regions.



## 📥 Data Description

* **Source:** Historical rainfall data for India (1901-2015).
* **Format:** Time series data indexed by year with total annual rainfall values.
* **Size:** 115 years of data.



## 🔍 Analytical Techniques Used

* **Data Cleaning & Preparation:** Handling missing data, smoothing, and resampling as needed.
* **Visualization:** Using libraries such as Plotly and Matplotlib to create:

  * Time series plots showing rainfall trends over years.
  * Heatmaps or geographical plots if region-wise data is available.
* **Trend Analysis:** Using statistical methods like moving averages and regression to identify long-term trends.
* **Anomaly Detection:** Employing machine learning algorithms like Isolation Forest to detect outlier years with abnormal rainfall.
* **Forecasting:** Applying Prophet (a time series forecasting library) to predict rainfall for upcoming years.
* **Clustering:** Using KMeans to group years or regions with similar rainfall patterns.
* **Correlation:** Computing correlation coefficients to study relationships between rainfall and other variables.


## 🛠 Tools & Libraries

* **Python** (primary programming language)
* **Pandas** for data manipulation
* **Plotly** and **Matplotlib** for interactive and static visualizations
* **Scikit-learn** for clustering and anomaly detection
* **Prophet** for time series forecasting



## 🚀 Outcomes

* Clear visualizations illustrating the trends and fluctuations in rainfall across more than a century.
* Identification of years with anomalous rainfall, potentially linked to climatic events.
* Forecast models providing future rainfall estimates to aid in planning and policy-making.
* Groupings of rainfall patterns that may help understand climatic zones or shifts.

## ⚠️ Limitations

* Historical data may have inconsistencies or missing values affecting analysis accuracy.
* Forecasting is based on past patterns and may not fully capture future climatic changes.
* Regional variability may require more granular data for deeper insights.


