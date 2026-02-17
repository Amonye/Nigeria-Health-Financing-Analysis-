# Nigeria-Health-Financing-Analysis-
A python based project for analysing health financing

# Health Financing Indicators for Nigeria (1995-2014)

## Project Overview

Welcome to my analysis of health financing indicators in Nigeria! This project delves into the financial aspects of Nigeria's health sector over two decades, from 1995 to 2014. My goal was to uncover key trends, patterns, and insights into how healthcare is funded and utilized in the country, providing a clearer picture of its evolution.

## Dataset Description

The core of this project is the `health-financing-indicators-for-nigeria-4.csv` dataset. This dataset, sourced from reliable health statistics, provides a comprehensive look at various health financing metrics specific to Nigeria. It includes indicators such as private prepaid plans, government expenditure on health (both per capita and as a percentage of total government expenditure), total health expenditure (per capita and as a percentage of GDP), external resources for health, social security expenditure, and out-of-pocket expenditure. The data spans from 1995 to 2014, offering a valuable time series for historical analysis.

## Analysis Summary

My analysis began with a thorough Exploratory Data Analysis (EDA) to understand the dataset's structure, identify missing values, and clean the data. I renamed columns for clarity and converted data types as needed. Following the initial inspection and cleaning, I summarized key statistics and analyzed the distributions of important variables. I then performed advanced analysis, focusing on:
- Trends over time: Visualizing how each indicator has evolved from 1995 to 2014 using line plots.
- Indicator distributions: Understanding the spread and central tendency of each indicator's values using box plots.
- Average indicator values: Comparing the overall magnitude of different financing indicators through bar charts.
- Snapshot of the latest year: Examining the status of indicators in 2014 to understand the most recent situation.
- Key comparisons: Specifically analyzing the relationship between government expenditure on health and out-of-pocket expenditure.

##Key Findings

Through this analysis, I've uncovered several significant insights:

* High Out-of-Pocket Expenditure: Out-of-pocket expenditure consistently dominates private expenditure on health and represents a very large portion of total health expenditure, indicating a heavy financial burden on individuals for healthcare.
* Low Government Contribution: Government expenditure on health, both per capita and as a percentage of total government spending, remains relatively low compared to other financing sources, suggesting limited public investment in the health sector.
* Reliance on External Resources: External resources for health contribute a notable, though fluctuating, percentage to total health expenditure, highlighting the role of international aid or grants.
* Limited Private Prepaid Plan: Private prepaid plans constitute a very small fraction of private health expenditure, indicating an underdeveloped health insurance market.
* Stagnant Per Capita Expenditure: While per capita total health expenditure (PPP int. $) is the highest on average, its growth has been modest over the years, suggesting slow progress in overall health spending capacity.
* Diverging Trends**: A critical observation is the inverse relationship between 'General government expenditure on health as a percentage of total expenditure on health' and 'Out-of-pocket expenditure as a percentage of total expenditure on health'. As government contribution to total health expenditure decreased or remained stagnant, out-of-pocket spending tended to increase, emphasizing the direct impact of public financing shortfalls on citizens.

These findings suggest that Nigeria's health financing system heavily relies on individuals' direct payments, with government and other prepaid mechanisms playing a smaller role. This could have significant implications for equitable access to healthcare and financial protection.

## How to Replicate

To replicate this analysis, follow these steps:

1. Clone the Repository**: Start by cloning this GitHub repository to your local machine.
2. Ensure Python Environment**: Make sure you have Python 3.x installed along with the necessary libraries. You can install them using pip:
   
    pip install pandas matplotlib seaborn
    
3. Data Location: Place the `health-financing-indicators-for-nigeria-4.csv` file in the same directory as the Jupyter notebook or script you are running.
4. Run the Notebook/Script: Execute the Jupyter notebook cells sequentially or run the Python script. The analysis covers:
    *   Loading and initial inspection of the data.
    *   Data cleaning (removing metadata rows, dropping highly null columns, handling remaining NaNs).
    *   Renaming key columns (`GHO (DISPLAY)` to `Indicator`, `YEAR (CODE)` to `Year`, `Display Value` to `Value`).
    *   Generating descriptive statistics.
    *   Visualizing trends over time for each indicator.
    *   Plotting distributions of indicator values.
    *   Comparing average indicator values.
    *   Analyzing indicator values for the most recent year (2014).
    *   Comparing specific key indicators like government expenditure vs. out-of-pocket expenditure.

By following these steps, you will be able to reproduce all the analyses and visualizations presented in this project.
