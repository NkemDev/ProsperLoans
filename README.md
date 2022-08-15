# Communicate Data Findings
## by Nkemakolam Onyemachi


## Dataset

> The Original dataset is the Prosper Loans dataset it contains 113,937 rows with 81 columns on each loan, including loan amount,
> borrower rate (or interest rate), borrower income, Stated Monthly Income, Prosper Loan ratings, etc
> I merged assessing and cleaning steps into one to make it concise.

## Data Assess and Cleaning
> 1. Choose columns that are neccessary to this analysis.

> 2. Removed Duplicate rows

> 3. Removed Null values in Borrowers state, Borrower APR, ProsperRating (Alpha), Occupation, EmploymentStatus, DebtToIncomeratio.

> ListcreationDate column in string data type instead of date.

> 4. Changed Statedmonthlyincome to two decimal places since it is a currency value.

> 5. Changed listcategory to the string equivalent.


## Summary of Findings
> ### Univariate Exploration:
> 1.  The year with the highest loan application was in 2013 while the lowest was in 2009
> 2. The distribution in the Borrower APR in the histogram is multimodal with the largest peak from 0.30-0.37 while the smallest peak is 
> from 0.0-0.1 and 0.4.
> 3.  The debt to income ratio had was unimodal with the peak at 0.3.
> 4.  The distribution of the loan amount peaked around 4k and decreased. Thus the distrbution was rightly skewed.
> 5.  The monthlyincome distribution is very righly skewed with the montly income peaking at 5k and decreasing to about 0 at around 31k.
> 6.  In the Employment status, most people in data are employed that applied for loans.
> 7.  In the occupation category, the most were others and the least loan applicants were students.
> 8.  In the prosper rating category, most people that applied were in the 'C' rating category.
> 9.  Most people applied for 36 months when they applied for loans.
> 10. The highest number of loan applicants were for debt consolidation.
> ### For the Bivariate Exploration:
> 11. The prosper rating is negatively correlated to the Borrowers APR as the prosper rating increases, the borrower's APR reduces.
> The  correlation score is -0.96.
> 12. The loan amount is also negative correlated to the Borrowers APR with a correlation score of -0.43.
> 13. The prosper rating is postively correlated to the loanamount with a correlation score of 0.43
> 14. The investors has a weak correlation with the statedmontly income.
> 15. Investors like to invest with people with an AA rating.
> 16. The highest number of investors are in the business category, followed by student use and then home improvement in that order.
> 17. Interesting features in the bivariate explorations include:
> 18. In the clustered data chart, the first chart between the Proper rating and the Loan term, more people had 36 months loan term,
> with  the highest on 'A'.
> 19. "C" rating had the highest number with 60months loan term. The 'HR' only had loan term of 36 months.
> 20. In the employment status, the Employed category had the highest in loan term of 12, 36 and 60months while retired and part-time had 
> the lowest.
> 21. In the Employment status and Prosper rating category, the employed category had the highest count while the partime had the lowest 
> count against the category.
> 22. The statedmonthly income is not a strong factor to borrowing or lending. It is very interesting as it seems they look more on the 
> prosper rating score more closely as it is positively correlated to the investors and negatively correlated to the Borrower's APR.
> ### Multivariate Explorations:
> 23. It is noted that the graph is negative in the 'HR' category and tends to positve when it reaches the 'A' category and the 'AA' 
> category. The 'A' and 'AA' category has the lowest risk. It will be profitable to encourage them in this category to borrow more to get
> more profit.
> 24. The 'HR' has the highest borrowers APR and this category borrows only for 36 months. The least borrower's APR are those in the "AA" 
> category. In short the Borrowers' APR decreases as the Prosperrating increases.
> 25. Full time category in the Employment status has the lowest mean Borrower's APR while the unemployed has the highest mean APR.
> 26. The home improvement had the lowest mean borrowes' APR while the taxes category had the highes mean borrower's APR.
> 27. The number of investors increases as the prosper rating gets better. The highest mean of investors in the Loan term was in 60months 
> and in the "AA" category.
> 28. The relationship among the investors,ratings and the loan amount is a positive correlations that becomes strongly positive as the ratings improves. Thus 'AA' has a stong positive correlation with the investors. With better prosper ratings makes investors interested to lend.


## Key Insights for Presentation

> The borrower's APR decreases as the loan amount increases. 
> Applicants with "AA" category has the least borrowers' APR
> Investors are most interested in lending money to applicants that are interested in borrowing for business while most people apply for 
> debt consolidation.
> Investors loan money more to those with "AA" rating.
