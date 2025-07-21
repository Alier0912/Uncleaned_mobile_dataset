
# Mobile Dataset Cleaning and Exploratory Data Analysis

## Overview

This project demonstrates the use of Python for data cleaning and exploratory data analysis (E.D.A) on a raw mobile phone dataset. The workflow includes systematic data preprocessing, handling inconsistencies, and extracting actionable insights from the data.

## Data Cleaning Process

The raw dataset contained various inconsistencies such as extraneous characters, missing values, and irrelevant entries. The following steps were undertaken to ensure data quality:

- **String Cleaning:** Removed unwanted characters (`[`, `]`, `'`) from the `name`, `brand`, `price`, and `description` columns to standardize text fields.
- **Brand Normalization:** Stripped the prefix "Brand:" from the `brand` column and applied capitalization for uniformity.
- **Irrelevant Entries:** Excluded rows where the `name` column contained non-mobile product entries (e.g., promotional text).
- **Price Formatting:** Removed currency symbols and commas from the `price` column, converting it to a numeric type for analysis.
- **Missing Values:** Replaced missing or null prices with the mean price to maintain dataset integrity.
- **Duplicates:** Checked for and confirmed the absence of duplicate records.

## Exploratory Data Analysis (E.D.A) and Findings

The cleaned dataset enabled meaningful analysis, including:

- **Top Brands by Total Sales:** Identified the top 10 brands based on total sales value, highlighting market leaders.
- **Most Popular Phones:** Ranked the top 10 mobile phones by average price, providing insight into consumer preferences for premium devices.

Key findings include:
- Certain brands consistently dominate total sales, indicating strong market presence.
- The most popular phones tend to be higher-priced models, suggesting a consumer preference for feature-rich or flagship devices.

## Recommendations

Based on the analysis:
- **For Retailers:** Focus inventory and marketing efforts on top-performing brands and high-demand models to maximize sales.
- **For Manufacturers:** Invest in flagship and mid-to-high-end devices, as these attract significant consumer interest.
- **For Further Analysis:** Consider integrating sales volume data to complement price-based insights and provide a more comprehensive view of market trends.

---
*Awal Alier* : *Reading between the data!*

