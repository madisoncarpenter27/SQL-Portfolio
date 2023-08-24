# SQL-Portfolio
This repository showcases a range of projects in PostgresSQL, completed both independently and as part of SQL and data analytics courses. The README highlights my independent analyses.

**Loan Approval Analysis:**
The loan approval dataset is a compilation of financial records and related data used to assess the 
eligibility of individuals or organizations seeking loans from a lending institution. It includes information 
such as applicants' income, credit scores (CIBIL scores), the amount of loan requested, loan terms, the value 
of assets, educational background, and the final loan status (approved, rejected, etc.). Presented below are the 
findings derived from the comprehensive analysis I have conducted.

**1.** With an overall approval rate of 62%, the dataset indicates that the majority of loans have been approved. 
   It suggests that the bank has not been overly conservative or lenient in granting loans.
**2.** There's a slight difference in average income between approved ($5,025,904) and rejected ($5,113,825) loans.
   This indicates that while income plays a role, it might not be the primary factor in loan approval decisions.
**3.** There is a substantial difference in average CIBIL scores between approved (703) and rejected (429) loans.
   Lending institutions tend to favor applicants with higher CIBIL scores, indicating better credit history and reliability.
**4.** The minor differences in average loan amounts across different loan statuses and education levels suggests that these
   factors might not be the primary drivers in determining loan amounts. Other variables likely have a more substantial impact.
**5.** The approved total loan amount of $40,496,700,000 showcases the bank's extensive lending capacity and exposure to credit
   risk. Properly managing such a large loan portfolio is vital for ensuring financial stability.
**6.** The relatively similar average total assets for approved and rejected loans indicate that assets might not be the sole
   decisive factor for loan approval. Other attributes, such as creditworthiness, may carry more weight.
**7.** The strong positive correlation (0.799) between the bank's assets and approved loan amounts indicates that the bank's
   financial strength enables it to offer larger loans to approved applicants.




**Educational Finances in Alabama Analysis:**
The annual assessment of elementary and high school finances is conducted by the United States Census Bureau. This financial data has been arranged in two separate files: "districts.csv" for school districts and "alabama.csv" for the state of Alabama. This data spans the years 1993 to 2016. Initially, the dataset encompassed financial data from all 50 states and the District of Columbia. However, I narrowed down the dataset to focus exclusively on the state of Alabama and its corresponding school districts. I then performed data cleaning to address any irregularities in the naming conventions of school districts. Presented below are findings from my financial analysis.

**1.** The provided data showcases an increasing trend in the total revenue of Alabama schools from 1993 to 2016. This steady growth suggests a positive trajectory in funding over these years, which could signify an increased investment in education and improved resources for students.
**2.** The calculated percentages offer a breakdown of expenditure categories. The majority of funds are allocated to instruction and support services, highlighting a strong emphasis on essential educational functions.
**3.** The outcome suggests that 11 school districts in Alabama consistently have an average revenue exceeding $100,000. These districts likely have greater funding, which could improve educational programs and support for students.
**4.** The Mobile County School District achieved the highest total revenue in 2016, underscoring its potential to enhance student support services, professional development, school facilities, extracurricular activites, and much more.
**5.** Similarly, the Mobile County School District recorded the highest total expenditure in 2016. This indicates a significant investment in educational activities and resources to provide a well-rounded learning environment.
**6.** Moreover, the Mobile County School District recorded the highest enrollment in 2016. A larger enrollment attracts more funding but also demands increased expenditure to accommodate diverse educational needs. 
**7.** Categorizing districts by enrollment reveals a trend. Larger districts seem to exhibit higher average revenue and expenditure, implying a potential correlation between student count and financial capability.



**Personal Finance Analysis:**
I undertook a personal finance tracker project to manage and understand my financial behaviors over the last three months. I structured the project by creating two essential tables: categories and transactions. The categories include income, rent, utilities, personal_bills, dining_out, shopping, entertainment, and savings.

**1.** I calculated the total income, expenses, and savings for the months of June through August. The resulting insights showed that my total income over the period was $12,032.34, total expenses summed up to $7,435.99, and I managed to save $3,800.00. These insights offer a clear view of my financial activity and emphasize my successful focus on prioritizing savings in my financial journey.
**2.** The analysis indicated that my highest expenditure was on personal bills, amounting to $5,210.00. This category does include credit card bills, and certain credit card purchases overlap with categories such as shopping and dining out. This contributes to the inflated amount within the personal bills category. Regardless, I am adhering to a well-maintained spending budget.
**3.** I determined that 63.72% of my personal bills are dedicated to credit card payments. I've learned how credit card obligations impact my finances. This knowledge will help me make wiser choices about credit card usage, manage payments effectively, and consider ways to reduce credit card-related costs.
**4.** I identified the month in which I made the highest expenditures. The outcome was that July was the most significant spending month, totaling $2,700.35. This knowledge allows me to reflect on the factors that might have contributed to higher spending during that month and make informed decisions to manage my expenses more effectively in the future.
**5.** I spent $432.81 on non-essential categories, namely dining out, shopping, and entertainment. This is relatively low for three months of spending. As previously noted, these categories overlap with credit card payments, underscoring the need to be mindful of credit card spending since these transactions don't immediately impact my checking account.
