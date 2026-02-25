# IMF Reporting Delay Analysis (Global Economic Data)

## Overview
This project analyzes the IMF Special Data Dissemination Standard (SDDS) dataset to evaluate reporting delays across countries. The objective is to identify trends, patterns, and correlations that affect the timeliness of economic data reporting.

---

## Dataset
- Source: IMF SDDS Data Availability (2024Q3)
- Global country-level economic reporting records
- Includes reporting dates, table counts, and availability indicators

---

## Objectives
- Clean and preprocess global economic dataset
- Calculate reporting delays by country
- Identify countries with highest reporting delays
- Analyze temporal trends in reporting delays
- Evaluate correlation between number of tables reported and delay duration

---

## Key Analysis Performed

- Data cleaning & preprocessing
- Handling missing values
- Data type conversion
- Delay computation
- Country-level aggregation
- Descriptive statistics
- Correlation matrix analysis

---

## Key Visualizations

- Bar Chart: Top 10 countries with highest reporting delays
- Area Chart: Trend of reporting delays over time
- Diverging Heatmap: Correlation between reporting tables and delays

---

## Key Insights

- Significant variation in reporting delays across countries.
- Temporal analysis shows fluctuations suggesting structural inefficiencies.
- Correlation between number of tables and delays is limited, implying systemic factors drive delays.
- Highlights importance of improving global reporting transparency.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## How to Run

1. Install required libraries:
   ```
   pip install pandas numpy matplotlib seaborn openpyxl
   ```
2. Open:
   ```
   final_code_DataExplore.ipynb
   ```
3. Run all cells sequentially.
