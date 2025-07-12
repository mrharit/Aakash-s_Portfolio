# [Project 1: Spotify HIT Prediction, Dissertation project(Machine Learning)](https://github.com/mrharit/Dissertation_project)

This is a project I did for my masters dissertation, where I build a prediction system for spotify dataset.

* Imported and preprocessed Spotify track data, including various audio features like tempo, danceability, and more.
* Performed EDA to understand the distribution and relationships of features within the dataset, including visualization of audio metrics.
* Implemented machine learning models to predict target variables based on the audio features, likely involving splitting the 
data into training and testing sets.
* Evaluated model performance using metrics such as accuracy, precision, recall, possibly involving cross- validation. 
* Created visualizations to present the findings and model performance, ensuring the results are actionable.
  
  I have also done an entire walkthrough video on youtube for the amazon price scapper and how you can build one too. [Click Here For Youtube Video](https://youtu.be/h-Ctr6KVcUY)

# [Project 2: Top UK Youtubers 2024 Dashboard using Excel, SQL and PowerBI](https://github.com/mrharit/Excel_SQL_PowerBI)

The main goal is to find out who the top YouTubers are in 2024 to decide on which YouTubers would be best to run marketing campaigns throughout the rest of the year.

What is the ideal solution?
To create a dashboard that provides insights into the top UK YouTubers in 2024 that includes their

subscriber count
total views
total videos, and
engagement metrics
This will help the team make informed decisions about which YouTubers to collaborate with for their marketing campaigns.

* Designed and implemented an interactive dashboard to identify the top-performing UK YouTubers based on subscriber count, videos uploaded, and total views, enabling data-driven marketing decisions.
* Analyzed reach, engagement, and potential revenue to recommend YouTube channels best suited for different campaign types (e.g., product placement, influencer marketing), optimizing ROI.
* Data Quality Assurance: Conducted thorough data quality checks, including row/column validation, data type verification, and duplicate removal, ensuring the accuracy and reliability of insights.
* Strategic Marketing Insights: Delivered actionable recommendations backed by data-driven justifications, helping the marketing team prioritize high-performing YouTube channels for future collaborations.
*  Created detailed documentation covering data sources, transformation processes, and analysis conclusions, ensuring the solution's reproducibility and maintainability for future updates.

# [Project 3: Road Accident Dashboard using Excel](https://github.com/mrharit/Road_Accident_Dashboard_Excel)

The Road Accident Data Dashboard is an Excel-based analytical tool designed to provide insights into road accident trends, causes, and statistics. This dashboard helps users analyze accident data through interactive charts, pivot tables, and automated calculations.

* Requirement Gathering and KPI Identification: Defined key metrics and KPIs for a Road Accident Dashboard in collaboration with stakeholders.
* Data Cleaning and Standardization: Imported raw data into Excel, handled missing values, and standardized formats for accurate analysis.
* Data Analysis and Insights: Calculated total casualties, analyzed data by accident severity, vehicle type, and road conditions.
* Visualization and Dashboard Creation: Created interactive charts and an intuitive dashboard layout to present key insights.
* Advanced Excel Techniques: Used conditional formatting, pivot tables, and Excel macros to automate tasks and enhance data analysis.

# [Project 4: Walmart Data Analysis using SQL and Python](https://github.com/mrharit/Walmart_Python_SQL_Project)

This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. We utilize Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions. The project is ideal for data analysts looking to develop skills in data manipulation, SQL querying, and data pipeline creation.

* Designed and implemented a complete data analysis pipeline — from data acquisition using the Kaggle API, through data cleaning and transformation with Python, to loading and querying in SQL databases (MySQL & PostgreSQL).
* Integrated both MySQL and PostgreSQL using SQLAlchemy, showcasing adaptability and proficiency in managing data across multiple relational database systems.
* Solved real-world business problems using complex SQL queries, including revenue trend analysis, profit margin evaluation, and customer behavior analysis by city, branch, category, and time.
* Created a custom feature (Total Amount) to enhance downstream SQL analysis — demonstrating strong analytical thinking and understanding of business KPIs.
* Maintained a well-organized project layout with dedicated folders for raw data, SQL queries, notebooks, and scripts, plus full documentation in Markdown — making it GitHub portfolio-ready and recruiter-friendly.

# [Project 5: PowerBI Sales Dashboard](https://github.com/mrharit/PowerBI_Sales_project)

This project aims to analyze sales data from various plants across different countries. The dataset includes information on product sales, costs, and geographical details. The goal is to derive insights that can help optimize sales strategies and improve overall business performance.

* Built a Power BI dashboard to visualize sales performance, cost metrics, and product trends across global regions — enabling data-driven business decisions at a glance.
* Conducted in-depth analysis of Sales vs. Cost of Goods Sold (COGS) to uncover high-performing products and profit margin drivers across different markets.
* Leveraged latitude, longitude, and address-level data to map sales trends across countries and regions, providing insights into location-based performance and growth opportunities.
* Utilized transaction timestamp data to analyze seasonality, peak sales periods, and time-based trends, supporting optimized sales strategy and resource allocation.
* Analyzed Price vs. Quantity vs. Revenue to evaluate pricing strategies, helping identify price sensitivity and product demand elasticity.

---

# ⏳ Time Series Forecasting Portfolio


## ⚡ [1. Power Consumption Forecasting using LSTM (Deep Learning)](https://github.com/mrharit/Power-Consumption-Forecasting-with-LSTM)

**Objective**: Predict household electricity consumption using historical smart meter data and LSTM neural networks.

- Preprocessed raw power consumption data from `.txt` format, combining date and time into datetime indices.
- Performed exploratory analysis on voltage, intensity, and sub-metered energy usage across circuits.
- Built and trained LSTM models using Keras/TensorFlow to capture sequential dependencies in power usage.
- Forecasted future energy consumption with visualized comparison against actual values, supporting smart energy grid decisions.
- Applied feature scaling, sequence windowing, and RMSE-based model evaluation.

> **Tools**: Python, Pandas, Seaborn, TensorFlow/Keras, Matplotlib

---

## 🥂 [2. Champagne Sales Forecasting (ARIMA Model)](https://github.com/mrharit/Time-Series-Analysis-and-Forecasting-Perrin-Freres-)

**Objective**: Forecast monthly sales of champagne from 1964 to 1972 using classical time series methods.

- Cleaned and transformed historical monthly sales data.
- Conducted seasonal decomposition to understand trend, seasonality, and noise in the sales data.
- Built ARIMA models and selected optimal parameters using AIC/BIC.
- Generated forecasts for future sales and visualized predictions alongside confidence intervals.

> **Tools**: Python, Pandas, Statsmodels, Matplotlib

---

## ✈️ [3. Airline Passenger Forecasting (ARIMA + Seasonality)](https://github.com/mrharit/Airline-Passenger-Forecasting-Project)

**Objective**: Predict airline passenger growth using monthly data from 1949 to 1960.

- Loaded and parsed time-series formatted data using pandas.
- Applied moving average and decomposition techniques to identify yearly seasonality and long-term trends.
- Implemented ARIMA-based forecasting and evaluated with visual overlays and residual diagnostics.
- Used the model to forecast future demand for air travel, assisting strategic planning.

> **Tools**: Python, Statsmodels, Pandas, Seaborn

---

## 🪑 [4. Furniture Sales Forecasting using Superstore Dataset](https://github.com/mrharit/Furniture-Sales-Forecasting-Superstore-Dataset)

**Objective**: Forecast monthly sales for the "Furniture" category in the Superstore dataset.

- Filtered and aggregated transactional data based on `Order Date`.
- Applied classical ARIMA modeling to perform rolling forecasts for inventory planning.
- Demonstrated trends in business seasonality and consumer behavior.
- Created reproducible code with clear visualizations to support data-driven decision-making.

> **Tools**: Python, Pandas, Statsmodels, Excel

---



