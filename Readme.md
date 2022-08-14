# DataSet
* The data used for this analysis was gotten from kaggle through this [link](https://www.kaggle.com/code/zeadomar/preliminary-eda-of-prosper-loan/data)
* The data tends to investigate the prosper rating of loan.

# Summary
1. The dataset consist of 113937 observations and 81 features
2. Some of the features includes Prosper rating, estimated loss, borrower rate, lender yield etc.
3. Some of the columns contains high missing values which includes GroupKey, LoanFirstDefaultedCycleNumber, ScorexChangeAtTimeOfListing, ProsperPrincipalOutstanding, ProsperPrincipalBorrowed, ProsperPaymentsOneMonthPlusLate, ProsperPaymentsLessThanOneMonthLate, OnTimeProsperPayments, TotalProsperLoans, TotalProsperPaymentsBilled, CreditGrade, ClosedDate.
4. The data also has columns with high cardinality
## Cleaning
5. Columns with more than 50% missing values were removed
6. All the columns with high cardinality were removed

# Insight
1. The data set used for the analysis is unclean and consist of missing values, some effort were made to clean the data by removing the columns with missing values above 50% and the rows with largee missing values were also removed. Also, columns with high cardinality were also removed. After the cleaning the shape of data used for the analysis is 84853 rows and 65 columns
2. One of the finding shows that the debt to income ratio increases as monthly income also drops which shows that there is an inverse relation.
3. There exist an increasing trend in loan payment as the quarter increases for each year.
4. Among the highest earning profession includes doctor, judge, pharmacist etc and the least earning occupation includes students
5. As the income range increases the loan payment also increases
6. Employed person tends who earn high monthly income tends to have a low debt to income ratio
7. With the increase in term the borrower rate also increases and well has the prosper rating


<!--    - Part_I_notebook.ipynb
   - Part_I_notebook.html or pdf
   - Part_II_notebook.ipynb
   - Part_I_slides.html
   - README.md
   - dataset (optional)


   jupyter nbconvert --to slides --post serve --no-input --no-prompt Part_II_slide_deck.ipynb
    -->