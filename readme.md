
# Prosper Loan Data Exploration, Visualization, and Communication of Findings
Data Source: [Prosper Loan Data](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to explore Prosper's loan data as an exercise in exploratory analysis and explanatory visualization and communication. I systematically explored the dataset, initially utilizing plots of single variables, then bivariate relationships, and finally multivariable plots. Afterwards I produced a short presentation illustrating noticeable properties, trends, and relationships that I discovered while attempting to find answers to the questions I posed about the data.


### Methods Used
* Descriptive Statistics
* Inferential Statistics
* Data Visualization

### Technologies
* Python
* NumPy
* Pandas, jupyter
* Matplotlib
* Seaborn


## Project Key Insights
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modeling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

Prosper's loan dataset was filled a large amount of data points. It was important to select and filter for a few variables to get, at first, a general understanding of the dataset before deploying more detailed analytical techniques. Overall, there were many commonalities across all borrowers despite different credit and financial characteristics. Some one the key takeaways were the following:

* In summary, we can say that Prosper borrowers, usually, have less than great credit ratings, reside in a handful of states across the United States, and are typically employed overall. The two most frequent areas of work borrowers work in are occupations categorized as other or professional.

* Although the range of original loan amounts varied from \\$1,000 USD to \\$35,000 USD on average borrowers had original loan amounts of \\$8,337 USD and the most frequent original loan amount was \\$4,000 USD.

* The most common monthly loan payment amount is \\$173.71 USD and the average amounts to \\$272.45 USD.

* In the case of borrower APR the most common APR was 35% while the average and median APRs amounted to 21%.

* As for the amount of time that prosper loans had attached for maturity there were three timeframes: 12, 36, and 60 months. 77% of all borrowers had loan term timeframes of 36 months.

* The average amount of open revolving credit accounts borrowers had at the time of their credit report being pulled for a prosper loan was 7, the median was 6, and the mode was 5.

* The average revolving credit balance was \\$17,598 USD while the most common value was \\$0.

* On average, the stated monthly income of all borrowers was \\$5,608 and the median amounted to \\$4,666. Interestingly enough, the range was quite large, with some borrowers reporting no monthly income and others as high \\$1.75 million.

* Debt-to-income ratios across all borrowers on average amounted to 27.6\% and a median value of 22%. The high levels of debt of some borrowers, as high as 10 times their income, pulled the average up. However, the most frequent debt-to-income ratio amounted to .18 or 18%.

* In the case of total prosper loans that borrowers, over 90% had either 1 or 2 loans. 70% had 1 loan while 20% had 2.

* Bank card utilization peaked at a maximum of 5.95 while averaging .56 across all borrowers. The most common value however was 0, indicating borrowers either had no current utilization or no credit.

* And in the case of prosper scores, scores ranging from 4 to 8 comprised over 67\% of all prosper scores across all borrowers within a range of 1-10. A small subset of borrowers were improperly marked with a value greater than prosper score rating system allows for.

## Needs of This Project
- data exploration/descriptive statistics
- data processing/cleaning
- writeup/reporting
