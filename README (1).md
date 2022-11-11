# (Prosper Loan Data Analysis)
## by (Sobia Arshad)


## Dataset

This dataset is financial dataset and this is related to the loan, borrowers, lenders, interest rates and stuffs like that. Prosper or Prosper Marketplace Inc. is a San Francisco, California based company specializing in loans at low interest rates to the borrowers. In this dataset, we are using the data from the Posper to analyse it and trying to find the pattern in the Prosper data.

This dataset contains information about loan listings and related variables including borrower as well as lender information. It contains variables related to Borrower such as credit rating, prosper rating etc. Moreover, the dataset also has lender information.

This dataset has 81 variables and contains 113937 entries. The variable that are explored in the dataset are the following 

Term : Amount of month customers opted for loan

LoanStatus : Current status of the loan like chargedoff, completed, defauted etc…

ProsperScore : Risk Factor score from 1 to 10. 10 being least risky

BorrowerAPR : The Borrower’s Annual Percentage Rate (APR) for the loan.

BorrowerRate : The Borrower’s interest rate for this loan.

ListingCategory..numeric. : Prosper rating for borrowers in numbers

EmploymentStatus : Current type of employment

Occupation : Occupation of borrower at the time of listing

EmploymentStatusDuration : How long the employee has been employed

ProsperRating..Alpha. : Prosper rating for borrowers in alphabets

StatedMonthlyIncome : Monthly income of the borrower

MonthlyLoanPayment : Monthly loan payment amount

LoanOriginalAmount : Original amount of the loan


## Summary of Findings

During this exploration we have following findings which are summarised as:

The length of most of the loans are 36 months. The ratings of most of the borrowers are among D to AA.only few borrowers have HR and E ratings.

The distribution of borrowers APR looks multimodal as ot has multiple peaks. 

borrower APR and loan amount is positively correlated when the Prosper ratings are from HR to B, but the correlation is turned to be negative when the ratings are B,Aand AA.

Borrower APR is negatively corelated to Loan amount.

Term here seems to have a significant effect on Borrower's APR and Loan amount.Mostly loan term is 60 months(5years).
APR for 3 years lon(36 months) is higher than the APR for 5 years(60 months)loan.

APR is higher than BorrowersRate(As APR in this prosper system is teh interest rate plus some additional fee/cost charged for that loan application).

with better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.

I also found that the loan amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan amount is also increased with the increase of loan term.

Borrowers with better rating also have larger monthly income and loan amount. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers.


## Key Insights for Presentation

For the presentation, I will try to focus on features that could affect the borrower APR, These are:

1-original loan amount
2-Prosper rating.

In the start the distribution of borrower APR and loan amount was shown.
Then, the relationship between APR Vs loan amountand APR VS Prosper rating was shown.
The effect of Prosper rating on APR and loan amount,APR and Term was also shown.