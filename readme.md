# Loan data from prosper
## by Swathi P


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
>
>In this data analysis we will be looking at factors which affect a loan’s outcome status?


## Summary of Findings

>1.Most of the loan status falls under current and completed and most of the borrowers are either Employed and Full-time workers.
>
>2.BorrowerAPR lies mostly between the range 0.1 to 0.3.An income range of 25000−49999 and 50000-99999 has majority of borrowers.
>
>3.The distribution of the DebtToIncomeRatio lies mostly between 0 to 1 .Most of the borrowers DebtToIncomeRatio lies between 0 to 0.6.
>
>4.Prosperscores of 4,6,8 are obtained by most of the borrowers.Very few borrowers have a prosperscore of 10.
>
>5.Borrower APR and LoanOriginalAmount have a negative correlation,which means,the higher the loan amount the lesser the borrower apr.
>
>6.ProsperScores are low for PastDue loans and higher for completed loans.
>
>7.PastDue,Defaulted and Chargedoff loans have higher DebtToIncomeRatio than current and completed.
>
>8.Full-time and employed borrowers are the most frequent borrowers for Chargedoff and defaulted loans,at the same time we can also observe that these category borrowers are the most who have completed the loans.
>
>9.Those with 25000-49999 income range have PastDue,Defaulted and Chargedoff loans,but they are the borrowers who have also completed maximum of the loans followed by 50000-99999 income range borrowers.
>
>10.Current loan Borrowers have higher Loan amounts than others.
>
>11.Borrowers who doesn't own home have Completed loans slightly higher than who own homes.Pastdue,defaulted and chargedoff loans have more number of borrowers who doesn't have home.Only current loan borrowers have more number of borrowers who own homes. Among all the categories of loan status,completed loans have lower BorrowerAPR.PastDue loans have higher Borrower APR.
>
>12.The highest BorrowerAPR is for borrowers who are not employed,followed by Other borrowers.Retired and Part-time employees have slightly lower rates than employed borrowers.
>
>13.For completed and current loans, borrowers who are employed have lower Borrower APR compartively than others.
PastDue loans have higher borrower apr,especially for those whose employment status is others and not employed.
In contrast to completed loans,for Defaulted loans,employed borrowers have higher Borrower APR.
Chargedoff loans also have higher Borrower APR,mainly for borrowers who are employed and not employed.
>
>14.From the plot,we can interpret that for every loan status category borrowers who own homes have higher loan amounts than borrowers who doesn't own homes.


## Key Insights for Presentation

>As we are predicting what factors affect the Loan status of a borrower,i started looking at individual variables like LoanStatus,EmploymentStatus,BorrowerAPR,ProsperScore,DebtToIncomeRatio,LoanOriginalAmount,IncomeRange,IsBorrowerHomeowner and IncomeVerifiable.
>
>ProsperScores are low for PastDue loans and higher for completed loans.
>
>PastDue,Defaulted and Chargedoff loans have higher DebtToIncomeRatio than current and completed.
>
>For completed and current loans, borrowers who are employed have lower Borrower APR compartively than others. PastDue loans have higher borrower apr,especially for those whose employment status is others and not employed.
>
>Borrower APR and LoanOriginalAmount have a negative correlation.
>
>In contrast to completed loans,for Defaulted loans,employed borrowers have higher Borrower APR. Chargedoff loans also have higher Borrower APR,mainly for borrowers who are employed and not employed.
>
>From the plot,we can interpret that for every loan status category borrowers who own homes have higher loan amounts than borrowers who doesn't own homes.