# Stock_Market_Prediction

This project focuses on analyzing stock market data to understand trading patterns and predict buy or sell actions based on volume changes. The analysis involves data extraction, transformation, and visualization, followed by a specific condition-based trading strategy.

**Project Description**
The dataset used in this project contains stock market data with fields such as time, volume, and other relevant metrics. 
The following steps were performed:

**Data Extraction and Transformation:**
-Extracted necessary fields from the dataset.
-Changed the format of the time data to a consistent format for analysis.

**Data Visualization:**
Plotted various charts to visualize stock market trends and trading volumes.

**Trading Strategy:**
Applied a condition-based approach where:
If the difference in volume between two time points is high, it indicates shares were purchased.
If the difference is low, it indicates shares were sold.

**Volume Analysis:**
Calculated the difference in volume between consecutive time points.

**Computed the cumulative volume:**
If the current volume is greater than the previous volume, the difference was added to the cumulative volume.
If the current volume is less, the difference was subtracted from the cumulative volume.

**Dataset**
The dataset is in CSV format and includes columns for time, volume, and other stock market metrics. Ensure that the dataset file is named stock_market_data.csv.

**Requirements**
Python 3.x
Pandas library
Matplotlib or any other plotting library
