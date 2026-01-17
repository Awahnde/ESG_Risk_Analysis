# ESG Risk Analysis
### ESG Risk Analysis of the SP 500 companies

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)

### Project Overview
This data analysis project aims to provide insights into the ESG Risk profile of SP 500 Global companies in the year 2023. By analyzing various aspects of the ESG data, the analysis project seeks to identify trends, make data-driven investment decisions, and gain deeper understanding of the ESG performance.

### Data Sources
ESG Data: The primary dataset used for this analysis is the "esg_data.csv" file, containing detailed information about each sale made by the company.(kaggle)

### Tools

- Excel - Data Cleaning [Download here](https://microsoft.com)
- SQL Server - Data Analysis
    - [Download here](https://microsoft.com)
- PowerBI - Creating reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

1. What is the overall sales trend?
2. Which products are top sellers?
3. What are the peak sales periods?

### Data Analysis

Include interesting code/dax formulas that I worked with

```sql
SELECT *
FROM table 1
WHERE cond = 2;
 ```

### Results
The analysis results are summarized as follows:

1. Most S&P 500 companies fall into Low to Medium ESG risk categories, while High and Severe risks are concentrated in a relatively small subset of firms.

<img width="698" height="403" alt="image" src="https://github.com/user-attachments/assets/01f90e85-c28c-444e-9cc2-7edb92abc760" />

The overall ESG risk distribution across the S&P 500 is skewed toward Low and Medium risk levels.
Out of the total companies analyzed, 179 fall into the Medium-risk category and 166 into Low risk, indicating that ESG exposure is generally manageable for most firms.
However, 73 companies are classified as High risk, while only 3 and 5 companies fall into the Severe and Negligible categories respectively, suggesting that ESG risk is concentrated rather than widespread.


2. The Energy sector exhibits the highest average ESG risk score at 32.2, while the Real Estate sector records the lowest at 13.5.
This indicates that ESG risk exposure varies meaningfully by sector, with Energy companies facing substantially higher ESG-related risks compared to Real Estate firms, which appear relatively lower risk across the index.







   
3. Product Category A is the best performing category in terms of sales and revenue.
4. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:

1. Invest in marketing and promotions during peak sales seasons to maximize revenue.
2. Focus on expanding and promoting products in Category A.
3. Implement a customer segmentation strategy to target high LTV customers effectively.

### Limitations

- Include all the information and circumstances that could affect the quality of the analysis

### References
1. SQL for Businesses
2. [Stack Overflow](https://stackoverflow.com)

