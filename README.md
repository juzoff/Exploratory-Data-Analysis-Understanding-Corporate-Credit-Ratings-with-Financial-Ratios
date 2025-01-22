# Exploratory-Data-Analysis-Understanding-Corporate-Credit-Ratings-with-Financial-Ratios
This project conducts a comprehensive analysis of corporate credit ratings for publicly traded U.S. companies, focusing on the relationship between credit ratings and financial ratios. The dataset includes financial ratios derived from balance sheets, income statements, and cash flow statements, with credit ratings classified into two binary categories: 1 = investment grade and 2 = junk grade.

The analysis involves importing the dataset, examining its structure, and addressing missing values through mean imputation. The project then performs statistical analysis, including ANOVA to investigate the relationship between financial ratios and the binary credit rating attribute. Pearson correlation (r-value) analysis is conducted to explore the strength and direction of relationships between financial ratios and the binary credit rating.

​The results of these analyses are compiled into a single dataframe for streamlined interpretation and are subsequently exported to a CSV file. These outputs are intended for further visualization and dashboard development using Power BI.

## Components:

1. Data Import and Preview:
   -  The dataset containing financial metrics and credit ratings is loaded, and the first few rows are displayed to understand its structure.
2. Data Structure Examination:
   - The data is inspected to determine data types, identify missing values, and evaluate its overall integrity.
3. Missing Value Handling:
   - Missing values in numerical columns (e.g., profitability, return metrics, and operational efficiency metrics) are replaced with column means.
   - Rows with missing or inconsistent categorical entries (e.g., credit ratings) are removed.
4. ANOVA Analysis:
   - ANOVA tests analyze the impact of credit rating categories (investment-grade vs. junk-grade) on various financial metrics (e.g., profitability, operational efficiency, financial health).
   - P-values and effect sizes (eta-squared) reveal statistically significant relationships between rating categories and numerical attributes.
   - **All selected financial attributes demonstrate a significant relationship with the target variable.**
5. Pearson Correlation Analysis:
   - Pearson correlation coefficients are calculated to explore the relationships between financial metrics, providing insights into how metrics such as profitability, operational efficiency, and financial health relate to one another.
   - Mean Differences Calculation and Contingency Table Analysis:
6. Mean differences across investment-grade and junk-grade categories are calculated to highlight variations in financial performance.
   - Contingency tables examine the distribution of corporations across categories like sectors, ratings, and agencies.
7. Data Preparation for Export:
   - Results from ANOVA and Pearson correlation analyses are formatted and combined into a single dataframe for easy analysis and visualization.
8. Output:
   - The final dataframe is exported to a CSV file for Power BI dashboard development.
9. Power BI Dashboard Development:
    - Dashboard 1: Comparing Financial Metrics - Investment Grades vs. Junk Grades
      - Profitability and Operational Efficiency Metrics: Visualizes key performance indicators such as margins, revenue growth, and asset turnover.
      - Financial Health and Return Metrics: Displays insights into metrics like debt-to-equity, return on assets, and return on equity.
    - Dashboard 2: Categorical Breakdown - Investment Grades vs. Junk Grades
      - By Ticker: Visualizes credit ratings for individual corporations.
      - By Sector: Highlights the distribution of credit ratings across industry sectors.
      - By Corporation: Identifies performance trends and rating distribution for specific corporations.
      - By Rating: Examines the frequency of each credit rating.
      - By Rating Agency: Illustrates rating distributions assigned by different agencies.


Filters allow users to analyze data by credit rating categories, view aggregated metrics such as averages and counts, and explore patterns and trends across financial dimensions.
