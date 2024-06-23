# Lending Club Case Study - By Saravanakumar PERUMAL
> Thir project work is for a consumer finance company which specialises in lending various types of loans to urban customers. In this project work I have demonstrated through various EDA ( Exploratory Data Analysis), to understand how consumer attributes and loan attributes influence the tendency of loan default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- This finance company should decide whether to approve the loan or not  based  on the loan application and available data with the company.
- Two types of risks are associated with the bank’s decision:	
   1) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company	
   2) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company	
- The data given from the company contains information about past loan applicants and whether they ‘defaulted’ or not.
- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- When a person applies for a loan,there are two types of decisions that could be taken by the company:
     1) Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:	
        a)	Fully paid: Applicant has fully paid the loan (the principal and the interest rate).	
	b) Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.	
	c) Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.
    2) Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.).		
	 Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)	

- Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
  The company can utilise this knowledge for its portfolio and risk assessment. 

- "Loan.csv" dataset is used in this project.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 - There are many columns contains NULL values and all the columns are removed during EDA Data Cleaning
- Conclusion 2 - Many columns are converted into numerical form or derived form so that data analysis produces better results
- Conclusion 3 - Many influencing features such as Loan status, Interest rate, Loan Amount, Annual Income, Employee length in the company and Home ownership etc., which are impacting the decision of loan approval are analyzed and repored as PDF file
- Conclusion 4 - Univariate, Bi-Variate and Multi Variate analysis is done on the data set

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- python 3 - Jupyter Note Book
- numpy library - version 1.26.4
- pandas library - version 2.2.1
- matplotlib library - version 3.8.3
- seaborn library - version 0.13.2
- plotly library - version 5.22.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project and the data was provided by [IIITB](https://www.iiitb.ac.in/) & [upGrad](https://www.upgrad.com/) learning platform.


## Contact
- Created by [Saravanakumar PERUMAL](https://github.com/Saravana2u/)- feel free to contact me!
- This project work repository is here : [Lending Club Case Study](https://github.com/Saravana2u/LendingClubCaseStudy).

