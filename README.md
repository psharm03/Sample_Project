# <Project Name> Data Exploration
## by Puneet Sharma


## Dataset

Brief description about dataset.
e.g. This data set contains 113,937 loans with 81 variables on each loan,
including loan amount, borrower rate (or interest rate), current loan status,
borrower income, and many others.


## Summary of Findings

Summary of findings. Example:
In the exploration, I found various positive and negative relationship between
different categories. After initial scan cleared few anomalies like converting
Date type columns as pandas dateType and engineer new columns for better
representation. Further exploration includes:
1) One with higher credit score is more likely to get better interest rate.
2) Investors are more likely to invest in a loan with person having higher
credit score.
3) People with high credit score are less likely to Default a loan.
4) Longer a person in employed more likely to be a home owner
5) People having more credit available to use from available credit limit are
more likely to get better interest rate.
6) Bigger loan get better interest rate


## Key Insights for Presentation

Example:
To find factors affecting loan outcome status. I spread out the categorical
variable to create dummies. Then get correlation among all variables. Then
created scatter and regression plot for interesting negative and positive
correlations. Major finding was one having high credit score and loan with lower
interest rate and lower bank card utilization likely going to have loan in
status ['Completed', 'Current', 'FinalPaymentInProgress']

Likewise one having higher credit score and lower bank card utilization and
higher available bank card credit and higher loan amount and lower investors
and higher income range are likely going to get better rate.

Lastly lower loan amount is more likely going to have
['Completed', 'Current', 'FinalPaymentInProgress'] status.
