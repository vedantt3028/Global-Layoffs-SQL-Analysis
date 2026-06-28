# 📊 Project Insights

## Overview

This document contains the key findings obtained after cleaning and analyzing the global layoffs dataset using MySQL.

---

# 🔎 Data Cleaning Insights

## Duplicate Records

- Duplicate rows were identified using SQL Window Functions.
- ROW_NUMBER() was used to detect repeated records.
- Duplicate entries were removed to maintain data accuracy.


## Missing Data

- Several columns contained NULL values.
- Missing values were analyzed and handled based on available information.


## Data Standardization

The dataset had inconsistent values.

Examples:

Before:
Crypto
Crypto Currency
CryptoCurrency


After:
Crypto


Standardized values improved analysis accuracy.


## Date Formatting

- Converted date column into proper SQL DATE format.
- Ensured consistent date representation.

---

# 📈 Exploratory Data Analysis Insights

## Company Layoffs

- Identified companies with the highest number of layoffs.
- Compared layoffs across different organizations.


## Industry Analysis

- Analyzed which industries were affected the most.
- Technology-related sectors showed significant layoffs.


## Country Analysis

- Compared layoffs across different countries.
- Identified countries with higher layoffs impact.


## Year-wise Trend

- Studied layoffs over different years.
- Observed changes in layoffs patterns over time.


## Funding Analysis

- Compared company funding levels with layoffs.
- Analyzed relationship between funding and workforce reduction.

---

# 🧠 Skills Demonstrated

## SQL Skills

- Data Cleaning
- Data Transformation
- Exploratory Analysis
- Aggregations
- Filtering
- Window Functions
- CTE
- Data Validation


## Tools

- MySQL
- MySQL Workbench
- GitHub


---

# Conclusion

This project demonstrates the complete data analysis workflow:

Raw Dataset → Clean Dataset → Analysis → Insights

It helped in understanding how real-world messy data is prepared and analyzed before making business decisions.
