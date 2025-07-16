# Predictive and Prescriptive Analytics with Python and Power BI

This project demonstrates the application of predictive and prescriptive analytics using Python and Power BI to derive actionable insights from real-world datasets. It covers forecasting, optimization, and data visualization techniques to aid data-driven decision-making.

## Table of Contents

  - [Introduction](https://www.google.com/search?q=%23introduction)
  - [Objective](https://www.google.com/search?q=%23objective)
  - [Tools and Technologies](https://www.google.com/search?q=%23tools-and-technologies)
  - [Datasets](https://www.google.com/search?q=%23datasets)
  - [Key Findings](https://www.google.com/search?q=%23key-findings)
      - [Predictive Analysis: Housing Prices](https://www.google.com/search?q=%23predictive-analysis-housing-prices)
      - [Prescriptive Analysis: Bike Sharing](https://www.google.com/search?q=%23prescriptive-analysis-bike-sharing)
  - [How to Run](https://www.google.com/search?q=%23how-to-run)
  - [Collaborators](https://www.google.com/search?q=%23collaborators)

## Introduction

In today's data-driven landscape, organizations leverage advanced analytics to uncover trends, predict future outcomes, and optimize operations. Predictive analytics enable forecasting by analyzing historical data patterns, while prescriptive analytics goes a step further by recommending the best course of action based on the insights derived.

This report focuses on applying predictive and prescriptive analytics using Python and Power BI to extract meaningful insights from two real-world datasets: a housing prices dataset (predictive analysis) and a bike-sharing dataset (prescriptive analysis). By leveraging data visualization, statistical modeling, and optimization techniques, the study aims to demonstrate how businesses can harness data for better decision-making.

## Objective

The primary objective of this project is to apply predictive and prescriptive analytics using Python and Power BI to extract actionable insights from real-world datasets. Specifically, it focuses on:

  * **Predictive Analysis:** Forecasting housing prices based on key attributes.
  * **Prescriptive Analysis:** Recommending strategies to optimize bike-sharing systems.

## Tools and Technologies

The following tools and technologies were utilized for this analysis:

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

The study is based on two publicly available datasets [14]:

  * **Housing Prices Dataset (Predictive Analysis):** [14]

      * Contains various attributes related to housing properties, including structural features (LotArea, Overall Qual, YearBuilt, GrLivArea), financial aspects (SalePrice - target variable), and condition/amenities (Fireplaces, Garage, KitchenQual) [14].
      * Used for predictive modeling to identify key factors influencing housing prices and develop models for price estimation [14].
      * Comprises 2,919 entries with 52 attributes, though only 1,460 records contain the "SalePrice" value [17, 20].

  * **Bike Sharing Dataset (Prescriptive Analysis):** [15]

      * Records bike-sharing activity across different times and conditions [15].
      * Includes temporal attributes (Season, Date, Year, Month, Weekday, Holiday), environmental factors (Temperature, Humidity, Wind Speed, Weather Conditions), and usage data (Casual & Registered Riders, Total Rentals) [15].
      * Applied prescriptive techniques to optimize bike availability by identifying peak demand periods and suggesting efficient bike distribution strategies, incorporating weather conditions as weighing factors [15].

## Key Findings

### Predictive Analysis: Housing Prices

  * **Correlation:** `OVERALLQUAL` (0.79), `GRLIVAREA` (0.71), `EXTERQUAL` (0.68), and `KITCHENQUAL` (0.66) showed strong positive correlations with `SALEPRICE`, indicating their significant influence on property value.
  * **Model Performance:** A Linear Regression model was used and outperformed a Decision Tree model, achieving a lower Mean Absolute Error (MAE) and Mean Squared Error (MSE), and a significantly higher R-squared score of 0.79. This suggests the linear model effectively captures the underlying patterns in housing prices.
  * **Outliers:** The analysis identified outliers in `GrLivArea` and `SalePrice`, which may affect model accuracy if not properly addressed.

### Prescriptive Analysis: Bike Sharing

  * **Demand Influencers:** Bike sharing demand is highly influenced by seasonal and weather-related factors. Warmer months (April-October) and summer season lead to increased bike sharing. Clear weather promotes higher usage, while rain/snow significantly deters it. Higher temperatures, low humidity, and low wind speeds are favorable conditions.
  * **User Behavior:** Registered users constitute a much larger portion (3M) of total rentals compared to casual users (620K), suggesting that registered users tend to utilize shared bikes more frequently.
  * **Optimization Model:** A Linear Programming (LP) model was developed to optimize bike distribution. The model minimizes bike relocation costs while ensuring supply meets demand, with adjustments based on seasonal and weather conditions. The model is implemented in Python using the PuLP library and integrated with Power BI for live adjustments and visualization of the optimal bike movement plan.

## How to Run

The project leverages Python for analytical modeling and Power BI for interactive data visualization and dashboards. The optimization model implemented in Python can be updated live via Power BI inputs for demand and weather adjustments, allowing for real-time prescriptive insights. Further details on setting up the environment and running the analysis can be found within the report.

## Collaborators

The following individuals contributed to this project:

  * Bushra, Bushra
  * Naw Mu Aye, Naw Mu Aye
  * Parekh, Jaya
  * Pawar, Pratiksha Ravindra
