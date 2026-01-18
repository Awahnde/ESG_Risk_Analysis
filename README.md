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

### Data Dictionary
| Column Name | Description |
|------------|-------------|
| Symbol | The unique stock symbol associated with the company |
| Name | The official name of the company |
| Address | The primary address of the company's headquarters |
| Sector | The sector of the economy in which the company operates |
| Industry | The specific industry to which the company belongs |
| Full Time Employees | The total count of full-time employees working within the company |
| Description | A concise overview of the company's core business and activities |
| Total ESG Risk Score | An aggregate score evaluating the company's overall ESG risk |
| Environment Risk Score | A score indicating the company's environmental sustainability and impact |
| Governance Risk Score | A score reflecting the quality of the company's governance structure |
| Social Risk Score | A score assessing the company's societal and employee-related practices |
| Controversy Level | The level of controversies associated with the company's ESG practices |
| Controversy Score | A numerical representation of the extent of ESG-related controversies |
| ESG Risk Percentile | The company's rank in terms of ESG risk compared to others |
| ESG Risk Level | A categorical indication of the company's ESG risk level |


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

1. What is the overall distribution of ESG risk across S&P 500 companies?
2. Which sectors exhibit the highest and lowest average ESG risk scores?
3. How does ESG risk vary across industries within the same sector?
4. Which ESG pillar (Environmental, Social, or Governance) is the primary driver of risk within each industry?
5. Are high-risk industries driven by a single dominant ESG pillar or by balanced risk across E, S, and G?
6. How does ESG risk change as controversy severity increases?
7. Are there companies with high ESG risk but low controversy levels (or vice versa)?
8. Is there a relationship between company size (e.g., number of employees) and ESG risk level?
9. What proportion of the S&P 500 workforce is employed by high or severe ESG-risk companies?
10. Are there geographic patterns in ESG risk concentration among S&P 500 companies?

### Data Analysis

Include interesting code/dax formulas that I worked with

```sql
SELECT *
FROM table 1
WHERE cond = 2;
 ```

### Results
The analysis results are summarized as follows:

#### 1. Most S&P 500 companies fall into Low to Medium ESG risk categories, while High and Severe risks are concentrated in a relatively small subset of firms.

<img width="698" height="403" alt="image" src="https://github.com/user-attachments/assets/01f90e85-c28c-444e-9cc2-7edb92abc760" />

The overall ESG risk distribution across the S&P 500 is skewed toward Low and Medium risk levels.
Out of the total companies analyzed, 179 fall into the Medium-risk category and 166 into Low risk, indicating that ESG exposure is generally manageable for most firms.
However, 73 companies are classified as High risk, while only 3 and 5 companies fall into the Severe and Negligible categories respectively, suggesting that ESG risk is concentrated rather than widespread.

 
#### 2. ESG risk varies significantly across sectors, with Energy companies facing the highest exposure and Real Estate firms the lowest.

<img width="736" height="379" alt="image" src="https://github.com/user-attachments/assets/8f1738a9-a206-439b-92c5-6968f438a16a" />


The Energy sector exhibits the highest average ESG risk score at 32.2, while the Real Estate sector records the lowest at 13.5.
This indicates that ESG risk exposure varies meaningfully by sector, with Energy companies facing substantially higher ESG-related risks compared to Real Estate firms, which appear relatively lower risk across the index.







   
5. Product Category A is the best performing category in terms of sales and revenue.
6. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

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

