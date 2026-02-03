# Credit-Card-Data-Analysis

## Objective
This project focuses on analyzing credit card customer acquisition, spending, and repayment behavior using pyhton. The goal is to understand customer behavior patterns, evaluate bank profitability, and generate actionable insights related to credit risk, collections, and targeted marketing in a real-world banking scenario.

The analysis is based on a case study simulating a global bank operating across multiple cities and customer segments.

## Business Objective
The objective of this project was to analyze credit card transaction and repayment data to:
  - Identify high-value and high-risk customer segments.
  - Understand spending and repayment patterns across cities, age groups, and product types.
  - Support data-driven decision-making for credit risk management and marketing strategies.

## Data Description.
The project uses three datasets.
1. Customer Acquisition data
   - Customer demographics(age, city, credit limit, product type)
2. Spend Data
   - Customer spending across categories, cities, and time periods.
3. Repayment Data
   - Monthly repayment amounts made by customers.

## Data Cleaning & Preprocessing.
Key data quality issues were identified and handled using Python:
- Replaced customer age values below 18 with the average age.
- Capped spending amounts exceeding the customer's credit limit at 50% of the limit.
- Replaced repayment amounts exceeding the credit limit with the limit value.
- Standardized date formats for monthly and yearly analysis.

## Exploratory Data Analysis(EDA)
Using Pandas and NumPy, the following analyses were performed.
- Counted average customers and transaction categories.
- Calculated average monthly spend and average monthly repayment per customer.
- Analyzed spending behavior across cities, age groups, and product categories.
- Identified top 5 product types and highest spending cities.
- Determined age groups contributing the highest spending.
- Identified top 10 customers based on repayment amount.

## Profitability Analysis
- calculated monthly profit as:
  Monthly Repayment - Monthly Spend.
- Applied a 2.9% monthly interest rate on positive monthly profit values.
- Computed interest-based profit earned by the bank for each month.

## Trend & Visualy Analysis:
Visualizations were created using Matplotlib and Seaborn to highlight:
- City-wise monthly comparison of total spending.
- Yearly comparison of spending on air tickets.
- Monthly spending trends across different product categories.
- Seasonal patterns in customer spending behavior.

# Key Insights
- Certain cities consisitently contributed higher transaction volumnes and revenue.
- Specific age groups showed higher spending behavior and repayment capacity.
- A small set of customers contributed significatnly to overall repayments.
- Product categories exhibited seasonal spendin patterns.
- Profitability varied month-over-month basedon customer repayment behavior.

# Tools and Technologies:
- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn.
- Data format : CSV

# Outcome
The project delivered a comprehensive analysis of credit card customer behavior and bank profitability. Insights fromthis analysis can support.
- credit risk assessment and fraud monitoring.
- customer segmentation and targeted marketing.
- Revenue optimization and collection strategies.

# Conclusion
This project demonstrates and end-to-end analytics workflow,from data cleaning and exploratory data analysis to profitability calculation and business storytelling, closely resembling real-world financial analytics and banking use cases.
