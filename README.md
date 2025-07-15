# **Data Science Internship at Prodigy Infotech**

## **Task 5 Submission:**

Welcome to my submission for Task 5 of the Data Science Internship at Prodigy Infotech. This project performs data cleaning, preprocessing, and exploratory data analysis (EDA) on the US Accidents (2016–2021) dataset.
The dataset contains information about traffic accidents in the United States, including location, time, weather conditions, and road features.
The goal is to discover trends, patterns, and insights that can help in understanding accident severity and factors contributing to road incidents.

## Dataset Description
____________

* Source: US Accidents Dataset (Kaggle)

* Size: ~7.5 million accident records

* Timeframe: February 2016 to December 2021

## Key Columns:
ID, Severity, Start_Time, End_Time, Start_Lat, Start_Lng, City, State, Temperature(F), Visibility(mi), Wind_Speed(mph), Distance(mi), and road feature indicators (Bump, Crossing, Junction, Traffic_Signal, etc.).

# Data Preprocessing
* Handling missing values
* Outlier detection and treatment (IQR method / clipping)
* Feature engineering (extracting hour, weekday, month)
* Transformation for skewed numerical features

## Exploratory Data Analysis
____________

* Univariate Analysis: Accident severity distribution, weather-related factors
* Bivariate Analysis: Relations between severity and other features
* Time-Based Trends: Accidents by year, month, weekday, and hour
* Road Features: Impact of junctions, bumps, traffic signals
* Geospatial Analysis: Accident density and hotspots

## Hotspot Map

An interactive hotspot map was created using Folium to visualize accident density across the United States.

👉 Preview:![Hotspot Map](https://github.com/AswathyD31/PRODIGY_DS_05/blob/f3a6cccb76c49e99f32f5a0b5163adad5db87bba/hotspot.JPG)

## Key Insights
___________

* Major accident hotspots are in cities like Los Angeles, Houston, and Dallas.

* Many accidents occur in areas lacking traffic signals and calming measures.

* Adverse weather conditions (low visibility, rain) often coincide with higher severity.

* Rush hours (morning & evening) see the highest accident frequency.

 ## Visualizations
 __________
 
* Correlation heatmaps
* Boxplots (before and after outlier treatment)
* Count plots and bar charts for city/state-wise analysis
* Time-series plots for seasonal patterns
* Hotspot map for accident density

## Tools and Libraries Used
__________________

* **Language:**  Python

* **Libraries:**  Pandas, NumPy, Matplotlib, Seaborn, Plotly, Folium, Scikit-learn

## Future Work
_________

* Build predictive models for accident severity.

* Develop an interactive dashboard for better visualization.

* Analyze additional features like weather and traffic patterns in depth.

This project was a great learning experience under the Prodigy Infotech Internship program, enhancing my skills in data preprocessing, visualization

🙏 Thank you for reviewing my submission!

