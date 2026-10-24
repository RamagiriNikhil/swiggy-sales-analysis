# Swiggy Sales Analysis | Python Data Analytics Project

## Project Overview

The **Swiggy Sales Analysis** project explores food-related records from January 1 to August 31, 2025, to understand food-category performance, popular dishes, geographic differences, time-based trends, and customer ratings.

The project uses Python-based exploratory data analysis (EDA) to identify patterns and develop data-driven business recommendations.

## Business Problem

Swiggy operates across multiple cities and offers a wide variety of vegetarian and non-vegetarian food items. Understanding recorded price patterns, popular dishes, geographic performance, time trends, and customer ratings can help identify areas that may require business attention.

The objective is to analyze the available dataset to understand which food categories, dishes, locations, and time periods contribute most to the total recorded price value while identifying opportunities to improve business performance and customer satisfaction.


## Project Objectives

- Compare Veg and Non-Veg categories by total recorded price value and average price per record.
- Identify the most frequently appearing dishes.
- Analyze state-level and city-level performance.
- Examine monthly, weekday, and quarterly trends.
- Evaluate customer ratings and identify restaurants with relatively low average ratings.
- Develop recommendations based on the observed patterns.

## Tools and Technologies

- **Python** – Data analysis and calculations
- **Pandas** – Data cleaning, grouping, aggregation, and analysis
- **NumPy** – Food-category classification
- **Matplotlib** – Static data visualizations
- **Plotly** – Interactive charts

## Dataset

The project uses an Excel dataset containing food-related records, with fields including:

- `Order Date`
- `Dish Name`
- `Price (INR)`
- `Rating`
- `Rating Count`
- `Restaurant Name`
- `City`
- `State`

The dataset covers January 1 to August 31, 2025.

## Methodology

### 1. Data Understanding

- Loaded the Excel dataset into a Pandas DataFrame.
- Examined the dataset dimensions, column names, data types, and summary statistics.

### 2. Data Quality Checks

- Checked missing values and exact duplicate records.
- Identified zero or negative prices.
- Checked ratings outside the expected 1–5 range.
- Converted date and numeric columns into appropriate data types.

### 3. Feature Engineering

- Classified dishes into Veg and Non-Veg categories using keyword matching.
- Created year-month, weekday, and quarter fields for time-based analysis.

### 4. Exploratory Data Analysis

- Calculated headline KPIs.
- Compared food categories and popular dishes.
- Analyzed state and city performance.
- Examined monthly, weekday, and quarterly patterns.
- Evaluated rating distributions and restaurant-level average ratings.

### 5. Data Visualization

Used Matplotlib and Plotly to present category comparisons, rankings, geographic performance, time trends, and rating patterns.

## Key Insights

1. **Overall performance:** The dataset contains 197,430 records with a total recorded price value of approximately ₹5.30 crore and an average price of ₹268.51 per record.

2. **Food-category performance:** Veg contributes approximately ₹3.06 crore (57.71%) of the total recorded price value, compared with ₹2.24 crore (42.29%) for Non-Veg. Non-Veg has a higher average price per record of ₹337.47, compared with ₹233.54 for Veg.

3. **Popular dishes:** Choco Lava Cake appears most frequently, with 303 records, followed by Veg Fried Rice with 243 and Chicken Sausage with 227.

4. **Geographic performance:** Karnataka has the highest total recorded price value among states, at approximately ₹54.57 lakh. Bengaluru leads the city analysis with the same aggregate value.

5. **City-level differences:** Bengaluru has 20,077 records and an average price of ₹271.79 per record. Lucknow has 10,192 records but a higher average price of ₹305.86 per record.

6. **Time trends:** January has the highest monthly total, at approximately ₹68.25 lakh, while February has the lowest, at ₹62.69 lakh. Saturday records the highest weekday total, at ₹77.83 lakh, while Tuesday records the lowest, at ₹73.59 lakh.

7. **Quarterly performance:** Q2 has the highest total recorded price value, at approximately ₹1.99 crore, slightly above Q1 at ₹1.97 crore. Q3 is incomplete because the dataset ends in August.

8. **Customer ratings:** The overall average rating is approximately 4.34 out of 5. Veg has a slightly higher average rating of 4.35 than Non-Veg at 4.32.

9. **Restaurants needing attention:** Cafe 99 has the lowest average rating among restaurants with at least 20 rating records, at 3.69 across 78 records.

## Business Recommendations

- **Food categories:** Maintain the strong presence of Veg dishes while investigating opportunities to promote Non-Veg dishes, which have a higher average price per record.
- **Popular dishes:** Review frequently appearing dishes such as Choco Lava Cake and Veg Fried Rice to understand their contribution to overall performance and whether they merit further promotion.
- **Geographic performance:** Investigate the factors behind Bengaluru's high aggregate value and compare its dish mix and price distribution with Lucknow and Hyderabad.
- **Time trends:** Compare monthly and weekday patterns to identify periods with relatively higher recorded price totals. Avoid strong seasonal conclusions from a single eight-month period.
- **Customer satisfaction:** Review customer feedback for lower-rated restaurants, starting with Cafe 99 and Dreams Cafe, to identify potential areas for improvement.
- **Performance monitoring:** Track recorded price totals, record counts, average prices, and ratings together instead of relying on a single metric.

## Conclusion

This project demonstrates how Python-based exploratory data analysis can transform a large dataset into useful business insights. The analysis highlights differences between food categories, identifies frequently appearing dishes, compares geographic performance, reveals time-based patterns, and identifies restaurants that may benefit from further review.

The findings show that Veg contributes the largest share of total recorded price value, while Non-Veg has a higher average price per record. Bengaluru leads in aggregate recorded price value, and the overall average rating is approximately 4.34 out of 5.

The project strengthened practical skills in data cleaning, data validation, feature engineering, aggregation, KPI calculation, trend analysis, visualization, and business interpretation.

---

# 👨‍💻 Author

**Nikhil Ramagiri**

Aspiring Data Analyst | SQL | Power BI | Excel | Python

📧 Email:ramagirin45@gmail.com

🔗 LinkedIn: www.linkedin.com/in/nikhil-ramagiri-21b2a324a

🔗 GitHub: https://github.com/RamagiriNikhil

---

