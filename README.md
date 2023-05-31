# Loan Data from Prosper
## by Durowoju Oluwadamilola


## Dataset

[Prosper](https://www.prosper.com/) is a peer-to-peer lending marketplace that helps in facilitating loans. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This [Sheet](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) contains information about the dataset variables.


## Summary of Findings

In this exploration, I investigated factors that investors would consider before granting a loan such as income, employment status, reason for loan(listing category), estimated return, and some other factors. Since Prosper introduced the prosper rating, I also investigated this factor. I discovered that there is a relationship between stated monthly income and loan status affected by listing category. The average monthly income for completed loans is above $5000 while for delinquent loans, the average monthly income starts higher but there is a decrease (below $5000) till the loan is marked as default. Judging by the highest listing category which is Debt Consolidation, it can be said that most people collect loans to repay another loan which is a negative habit as it tends to affect the stated monthly income.

On the otherhand, the DebtToIncomeRatio is quite low for a large portion of borrowers on Prosper meaning, most borrowers are not in debt. A look at the IncomeRange suggests most borrowers earn quite well too and across the incomerange categories, there is a uniform distribution of the loan status.

For an investor, long term loans are recommended as they yield better returns as the Prosper rating serve as a good determinant factor for risk and return of loans.


## Key Insights for Presentation

I will present factors that influences loan application and repayment. Also for an investor, I will showcase prosperrating as an investment factor for determining loan profitability.

I will start by introducing the distribution of loan status, followed by listing categories, incomerange and monthlyloan payment. Then, I will present the relationships between these features of interest.
