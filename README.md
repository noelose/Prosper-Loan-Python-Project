# Prosper-Loan-Python-Project

## Introduction
- This is a dataset of Prosper Loan it's a comprehensive collection of information about loans and their associated borrowers. This dataset includes various features such as loan amounts, borrower credit ratings, employment status, and more, providing an excellent opportunity to analyze trends, relationships, and potential predictors of loan performance.

Interesting Relationships Between Other Features
While the primary focus was on the relationships between Loan_Original_Amount, Income_Range, and Loan_Status, there were several interesting relationships observed between other features in the dataset as well:

Employment Status vs Loan Amount: There is an observable relationship between Employment Status and the Loan Amount. Borrowers who are employed tend to request higher loan amounts compared to those who are unemployed or have unknown employment status. This is expected since employed individuals have a more stable source of income, which likely makes them eligible for larger loans. However, there were a few cases where unemployed or unknown borrowers requested higher loan amounts. These could represent exceptional cases such as loans secured by other assets or loans approved based on other factors..

Debt-to-Income Ratio vs Loan Amount: The Debt-to-Income Ratio is another interesting feature. Borrowers with higher ratios tend to request smaller loan amounts. This makes sense as individuals with high existing debt may struggle to take on additional loans or may not qualify for larger amounts. On the other hand, individuals with low ratios, indicating they have a better balance between their income and debt, are more likely to apply for larger loan amounts.

Homeownership Status vs Loan Amount: Another interesting relationship is between Homeownership Status and Loan Amount. Homeowners tend to request slightly higher loan amounts compared to renters. This might be because homeowners are seen as more financially stable, and they might use their property as collateral for larger loans. However, there are still many renters who apply for significant loan amounts, possibly due to other assets or creditworthiness factors that allow them to qualify.

Credit Score vs Loan Status: There is a noticeable connection between Credit Score and Loan Status. Borrowers with higher credit scores generally have better loan statuses and they are less likely to default. This suggests that individuals with good credit are more likely to be approved for loans and are better at managing their repayments. While, those with lower credit scores tend to default more frequently, which aligns with expectations around creditworthiness and loan risk.

Loan Amount vs Loan Term: The relationship between Loan Amount and Loan Term is also worth noting. Borrowers who request higher loan amounts tend to choose longer loan terms. This might be because they need more time to repay the larger loan, which makes sense from a financial planning perspective. Shorter loan terms are typically chosen for smaller loans, likely because they are more manageable and borrowers want to pay them off more quickly.


## Conclusion
### Main Findings
Income and Loan Amount: There is a clear correlation between income and loan amount, with higher income borrowers generally requesting larger loans. Middle income groups, such as 25,000 to $74,999, make up the majority of borrowers.

Credit Scores Impact on Loans: Borrowers with higher credit scores tend to request and receive larger loan amounts. This is expected as better credit scores signal financial reliability to lenders.

Homeownership Influence: Homeowners tend to borrow larger amounts compared to renters. This likely reflects the stability associated with homeownership, making these borrowers appear less risky to lenders.

Borrower APR: Higher APRs were typically associated with borrowers in lower income brackets or those with lower credit scores. This suggests that APRs reflect the perceived risk of the borrower.

Employment Status: Employed borrowers generally request higher loan amounts compared to those who are unemployed. This shows that employment status plays a role in determining loan amounts, with employed borrowers perceived as more financially stable.

Debt-to-Income Ratio: Borrowers with higher debt-to-income ratios tend to request smaller loans, indicating that they are carrying a higher amount of debt relative to their income, making them less likely to take on large loans.

Loan Terms: Borrowers requesting larger loan amounts often choose longer loan terms. This allows them to spread the repayment over time, making it more manageable.

Loan Status: Borrowers in lower income brackets and with lower credit scores showed a higher likelihood of defaulting on their loans, which is consistent with common lending practices where higher risk borrowers are more likely to default.

Income Range and Credit Score: Higher income ranges often correspond with higher credit scores, enabling these borrowers to access larger loans with better terms.



Steps Taken During Data Exploration
Data Cleaning: We addressed missing values and renamed unclear columns and standardize it for clarity and consistency.

Univariate Analysis: We explored individual variables such as income and loan amounts through histograms and boxplots, which revealed trends.

Bivariate Analysis: We analyzed relationships, like loan amounts vs. income ranges, using visualizations to understand how these variables interact.

Identifying Key Patterns: We found that higher incomes and better credit scores generally lead to larger loans, shedding light on loan approval factors.

Visualization: We used visualizations to reveal key relationships in the data, making complex patterns easier to understand.

We summarized key insights, such as the impact of income and credit scores on loan amounts, providing a clear view of the data's behavior.
