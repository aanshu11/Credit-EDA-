# Credit-EDA-CASE STUDY 
## BUSINESS OBJECTIVE 
This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.


In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.



## BUSINESS PURPOSE 
* Credit risk analysis will help the company to make a decision for loan approval based on the applicant’s profile. Which controls loss of business to the company and avoid financial loss for the company.
* As per criteria it’ll provide the loan to the merit list people and avoid the risk factor points.
* When a client applies for a loan, there are four types of decisions that could be taken by the client/company):
  * Approved
  * Cancelled
  * Refused
  * Unused Offer 


## APPROACH 

1. Importing Modules 
2. Reading the DATASET 
3. Data Cleaning 
    * Handling Missing Values
    * Type Casting 
    * Data Manipulation
    * Handling Outliers 
4. Univariate Analysis
5. Bi-variate Analysis


## Data Understanding 

Dataset link  - [Dataset](https://drive.google.com/drive/folders/16RQztUqCfJOlbooHqYlJrp6Q7iL65uZB).

This dataset has 3 files as explained below: 

1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.

2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.


## Libraries Used
* Numpy
* Pandas
* Matplotlib
* Seaborn

 
