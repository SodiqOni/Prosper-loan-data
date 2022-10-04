# (Loan Data from Prosper)
## by (Oni Sodiq Adesola)


## Dataset

The data consists of information regarding 113937 loan data from Prosper, including BorrowerAPR, ProsperRating, and other features. The dataset can be found here https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000, with features documentation available here https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000.


## Summary of Findings

In the exploration, I found that there was a strong relationship between the BorrowerAPR and EstimatedLoss. A very strong correlation exist between BorrowerAPR and EStimatedLoss i.e. the higher the BorrowerAPR the higher the EstimatedLoss and viceversa. A moderate negative correlation also exist between LoanOriginalAmount and both BorrowerAPR and EstimatedLoss. There is also an inverse relation between BorrowerAPR and both ProsperRating and IncomeRange i.e. the higher the ProsperRating and IncomeRange the lower the BorrowerAPR. Similarly, EstimatedLoss also have inverse relation with both ProsperRating and IncomeRange.

I also observed a negative correlation between InquiriesLast6Months and ProsperRating. It turns out that those that makes frequest enquiries tends to be desperate in need of money hence reducing their rating. A positive relationship also exist between ProsperRating and both StatedMonthlyIncome and LoanOriginalAmount. The higher the StatedMonthlyIncome And LoanOriginalAmount the higher the ProsperRating and viceversa. 

Outside of the main variables of interest, I verified the likely state to have highest number of defaulters. South Dakota(SD), seems to have high number of defaulters because their LoanAmount is quite more than their StatedMonthlyIncome. Also, some other factors might be responsible for this also.

## Key Insights for Presentation

For the presentation, I will be using the cleaned data from the proper data given for the analysis. My main focus is to determine those features that can help to decide Borrowers APR while granting loan likewise those features that affect the prosper rating of borrowers. To start with, I performed a univariate analysis by looking at the distribution of both BorrowerAPR and ProsperRating.

Afterwards, I conducted a bivariate analysis starting with looking at the correlation between BorrowerAPR and other numerical variables, then I introduced some categorical variables to check their relationship with BorrowerAPR using boxplot. Furthermore, I used boxplot to check for relationship between Prosperrating, EstimatedLoss and InquiriesLast6Months. Lastly, I looked at how LoanOriginalAmount affect ProsperRating and IncomeRange using boxplot, likewise how it affect Prosperrating and BorrowerAPR using regplot. 
