# Exploratory Data Analysis (EDA) on Air Quality in India Dataset

## Project Overview
This project analyzes daily city-level air quality records to uncover trends, seasonal patterns, pollutant correlations, and urban hotspots of pollution.

## Tools & Libraries
- Python
- Pandas – data cleaning & manipulation
- Matplotlib & Seaborn – data visualization
- Jupyter Notebook – analysis & presentation

## Final Summary of Insights:

### 1 - Missing Data:
- High missingness in Xylene, PM10, NH3, Toluene.
- City and Date were complete, enabling grouping and time-series analysis.
- After cleaning (NaN conversion + city-wise median imputation), most pollutants were usable; Xylene remained unreliable.

### 2 - Most Polluted Cities:
- Highest average AQI: Ahmedabad, Delhi, Patna, Gurugram, Jorapokhar, Brajrajnagar, Lucknow.

### 3 - Cities Above Safe Limit (>100 AQI):
- % of unsafe days: Ahmedabad (~97%), Delhi (~91%), Patna (~88%), followed by Gurugram, Jorapokhar, Brajrajnagar, Lucknow, Talcher, Bhopal, Jaipur.
- Indicates chronic pollution in major cities.

### 4 - Pollutant Composition:
- Major contributors: PM2.5, PM10.
- VOCs (Benzene, Toluene, Xylene) had sparse data → less reliable insights.

### 5 - Seasonal & Monthly Variation:
- Worst AQI in winter, better air in warmer months.
- Monthly trends show spikes during late autumn–winter pollution episodes.

### 6 - Weekday vs Weekend
- Slightly higher AQI on weekdays in some cities (likely traffic-related).
- Overall effect modest; varies by city.
