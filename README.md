# Melbourne Housing Price Recommendation Analysis
Data Visualization and Exploratory Data Analysis (EDA) of the Melbourne Housing market trends, geographical and distance analysis. 

## Overview

This project focuses on the Exploratory Data Analysis (EDA) and visualization of the Melbourne housing market, geographical and distance analysis. The goal was to transform raw property sales data into actionable recommendations, particularly aimed at potential buyers and investors.

The analysis identifies key factors driving property value, such as property type, distance from the CBD, and regional trends, allowing users to make data-driven decisions on where and what type of property to purchase.

## Key Features & Impacts

### **1. Dashboard 1: Melbourne Housing Market Trends (2016–2018)**

* **1.1. Overall Price Trend:** The Melbourne market experienced a period of high volatility, with a peak in **August 2017** followed by a noticeable cooling trend.
* **1.2. Regional Price Comparison:** There is significant price disparity across regions. **Southern Metropolitan** consistently maintained the highest median property price.
* **1.3. Sales Volume by Property Type:** **Houses (h)** dominated the market in terms of volume, accounting for the vast majority of sales compared to Units (u) and Townhouses (t).
* **1.4. Median Price and Total Sales Scorecard:** Over **48,433** total sales were analyzed over the 3-year period.

### **2. Dashboard 2: Melbourne Property Geographical and Distance Analysis**

* **2.1. Council Area Map:** High-value sales are heavily clustered in inner-city and select coastal/leafy inner-eastern postcodes, forming distinct hot zones.
* **2.2. Price v/s Distance:** A strong negative correlation exists; as distance from the CBD increases, the property price generally decreases.
* **2.3. Price by Distance bins** The sharpest drop in median price occurs immediately after the 10-15km bin, indicating where the market shifts from inner premium to outer suburban.
* **2.4. Sales volume by council:** Council Areas surrounding major infrastructure hub like Darebin City Counsil recorded the highest sales volumes.

## Technologies and Tools

| Category | Tool/Technology | Purpose |
| :--- | :--- | :--- |
| **Data Source** | `MELBOURNE_HOUSE_PRICES_LESS.csv` | Raw property sales dataset. |
| **Visualization** | **Tableau Desktop** | Used for data cleaning, aggregation, and generating the interactive analysis workbook (`.twb` file). |
| **Analysis Focus** | EDA, Data Cleaning, Data Transformation | Performed tasks like handling missing values and categorizing variables (e.g., property types, regions). |


## Project Files

* `MELBOURNE_HOUSE_PRICES_LESS.csv`: The clean source dataset used for analysis.
* `Melbourne Housing Price Recommendation for Buyers.twb`: The Tableau workbook containing all sheets and the final dashboard design.

## How to View the Dashboard

1.  Download the `Melbourne Housing Price Recommendation for Buyers.twb` file from this repository.
2.  Open the file using **Tableau Desktop**. (Note: This is a `.twb` file, which requires access to the original CSV data file to display correctly).
