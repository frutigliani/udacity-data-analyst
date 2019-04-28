# Dataset Exploration: Loan data from Prosper
## by Francesco Rutigliani


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

Prosper Marketplace is America's first peer-to-peer lending marketplace, with over $7 billion in funded loans (source: Wikipedia) 
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 
The dataset last update is 03/11/2014.

## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

The purpose of this project is to analyze the relationship between multiple variables which could affect the borrower's APR (annual percentage rate) using summary statistics and data visualizations.

The first section of the project (Univariate Exploration) explores some general characteristics of the loans:

- The maximum amount borrowed is less than 35,000 $ and the majority is less than 15,000 $.
- Loans have a fixed term: 1, 3 or 5 years. 3 years is the most common.
- Debt consolidation is the main reason to contract a loan.
- Average APR (annual percentage rate including fees) is 21,76%.

This section also provide a quick profile of the borrowers: 

- Most of the borrowers live in California, New York, Florida, Texas or Illinois.
- Approximately 84% of borrowers earn less than 100,000 $ per year.
- Most of borrowers have an employment duration less than 10 years.
- Slightly more than a half of borrowers is homeowner (they have a mortgage on their credit profile or provide documentation confirming they are a homeowner).

The second and third section (Bivariate and Multivariate Exploration) investigate the relationship between borrower's APR and the other variables:

- APR increased steadily from 2007 till 2011 then it started to decrease.
- There is a negative correlation between APR and loan amount. However, there is a significant variability for loans < 15,000 $.
- There is a positive correlation between APR and debt to income ratio. However, there is a significant variability for lower debt/income values.
- APR tends to be higher for lower income ranges. Curiously, not employed borrowers seem to get lower interest rates.
- There is not a significant relationship between loan term, employment duration and APR.


