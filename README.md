# Predictive and Prescriptive Analytics with Python and Power BI

[cite\_start]This project demonstrates the application of predictive and prescriptive analytics using Python and Power BI to derive actionable insights from real-world datasets[cite: 3]. It covers forecasting, optimization, and data visualization techniques to aid data-driven decision-making.

## Table of Contents

  - [Introduction](https://www.google.com/search?q=%23introduction)
  - [Objective](https://www.google.com/search?q=%23objective)
  - [Tools and Technologies](https://www.google.com/search?q=%23tools-and-technologies)
  - [Datasets](https://www.google.com/search?q=%23datasets)
  - [Key Findings](https://www.google.com/search?q=%23key-findings)
      - [Predictive Analysis: Housing Prices](https://www.google.com/search?q=%23predictive-analysis-housing-prices)
      - [Prescriptive Analysis: Bike Sharing](https://www.google.com/search?q=%23prescriptive-analysis-bike-sharing)
  - [How to Run](https://www.google.com/search?q=%23how-to-run)

## Introduction

In today's data-driven landscape, organizations leverage advanced analytics to uncover trends, predict future outcomes, and optimize operations. This report specifically focuses on using predictive analytics for forecasting and prescriptive analytics for recommending optimal courses of action based on derived insights. [cite\_start]The project applies these techniques to a housing prices dataset for predictive analysis and a bike-sharing dataset for prescriptive analysis, demonstrating how businesses can enhance decision-making through data visualization, statistical modeling, and optimization[cite: 3, 4, 5].

## Objective

The primary objective of this project is to apply predictive and prescriptive analytics using Python and Power BI to extract actionable insights from real-world datasets. Specifically, it focuses on:

  * [cite\_start]**Predictive Analysis:** Forecasting housing prices based on key attributes[cite: 6].
  * [cite\_start]**Prescriptive Analysis:** Recommending strategies to optimize bike-sharing systems[cite: 7].

## Tools and Technologies

[cite\_start]The following tools and technologies were utilized for this analysis[cite: 13]:

  * **Python:**
      * **Exploratory Data Analysis (EDA):** Pandas, Matplotlib, Seaborn
      * **Predictive Modeling:** Scikit-learn (Linear Regression, Decision Trees)
      * **Optimization & Decision Analysis:** Pandas, PuLP
  * **Power Query:**
      * Data Preprocessing & Cleaning
  * **Power BI:**
      * **Descriptive Analysis:** Bar Charts, Pie Charts, Card
      * **Exploratory Data Analysis (EDA):** Scatter Plot, Decomposition Trees
      * Interactive Data Visualization using dashboards
      * Trend & Pattern Identification through charts and heatmaps
      * Data Exploration & Filtering for deeper insights

## Datasets

[cite\_start]The study is based on two publicly available datasets[cite: 14]:

  * [cite\_start]**Housing Prices Dataset (Predictive Analysis):** [cite: 14]

      * [cite\_start]Contains various attributes related to housing properties, including structural features (LotArea, Overall Qual, YearBuilt, GrLivArea), financial aspects (SalePrice - target variable), and condition/amenities (Fireplaces, Garage, KitchenQual)[cite: 14].
      * [cite\_start]Used for predictive modeling to identify key factors influencing housing prices and develop models for price estimation[cite: 14].
      * [cite\_start]Comprises 2,919 entries with 52 attributes, though only 1,460 records contain the "SalePrice" value[cite: 17, 20].

  * [cite\_start]**Bike Sharing Dataset (Prescriptive Analysis):** [cite: 15]

      * [cite\_start]Records bike-sharing activity across different times and conditions[cite: 15].
      * [cite\_start]Includes temporal attributes (Season, Date, Year, Month, Weekday, Holiday), environmental factors (Temperature, Humidity, Wind Speed, Weather Conditions), and usage data (Casual & Registered Riders, Total Rentals)[cite: 15].
      * [cite\_start]Applied prescriptive techniques to optimize bike availability by identifying peak demand periods and suggesting efficient bike distribution strategies, incorporating weather conditions as weighing factors[cite: 15].

## Key Findings

### Predictive Analysis: Housing Prices

  * [cite\_start]**Correlation:** `OVERALLQUAL` (0.79), `GRLIVAREA` (0.71), `EXTERQUAL` (0.68), and `KITCHENQUAL` (0.66) showed strong positive correlations with `SALEPRICE`, indicating their significant influence on property value[cite: 46, 47, 48].
  * **Model Performance:** A Linear Regression model was used and outperformed a Decision Tree model, achieving a lower Mean Absolute Error (MAE) and Mean Squared Error (MSE), and a significantly higher R-squared score of 0.79. [cite\_start]This suggests the linear model effectively captures the underlying patterns in housing prices[cite: 71, 72, 73, 75].
  * [cite\_start]**Outliers:** The analysis identified outliers in `GrLivArea` and `SalePrice`, which may affect model accuracy if not properly addressed[cite: 59, 60].

### Prescriptive Analysis: Bike Sharing

  * **Demand Influencers:** Bike sharing demand is highly influenced by seasonal and weather-related factors. Warmer months (April-October) and summer season lead to increased bike sharing. Clear weather promotes higher usage, while rain/snow significantly deters it. [cite\_start]Higher temperatures, low humidity, and low wind speeds are favorable conditions[cite: 155, 156, 157, 158, 159].
  * [cite\_start]**User Behavior:** Registered users constitute a much larger portion (3M) of total rentals compared to casual users (620K), suggesting that registered users tend to utilize shared bikes more frequently[cite: 90, 91].
  * **Optimization Model:** A Linear Programming (LP) model was developed to optimize bike distribution. [cite\_start]The model minimizes bike relocation costs while ensuring supply meets demand, with adjustments based on seasonal and weather conditions[cite: 175, 176, 177]. [cite\_start]The model is implemented in Python using the PuLP library and integrated with Power BI for live adjustments and visualization of the optimal bike movement plan[cite: 179, 191, 192, 194, 195].

## How to Run

The project leverages Python for analytical modeling and Power BI for interactive data visualization and dashboards. [cite\_start]The optimization model implemented in Python can be updated live via Power BI inputs for demand and weather adjustments, allowing for real-time prescriptive insights[cite: 194, 195]. Further details on setting up the environment and running the analysis can be found within the report.

## Collaborators

The following individuals contributed to this project:

* Bushra, Bushra
* Naw Mu Aye, Naw Mu Aye
* Parekh, Jaya
* Pawar, Pratiksha Ravindra
