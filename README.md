# Wisabi-Bank-ATM-Transaction-Data-Analytics-Project
This data analytics project involves analyzing the ATM transactions data, which includes the Transactions fact table, Location dimension table, Customers Dimension table, Transaction Type Dimension Table, Hour dimension table, and Calendar dimension.

Wisabi Bank ATM Transactions Analysis Project.(Time Period from January to December 2022)

The purpose of this project is to analyze the ATM transaction data for Wisabi Bank to gain insights on customer behavior, ATM usage, and identify opportunities to improve the bank's services.

PROBLEM SOLVING FRAME WORK - The framework consists of 6 stages 
1. Business Issue Understanding - Understand the business problem
2. Data Understanding - Collect data to gain insights into its quality and relevance
3. Data Preparation - Clean, Transform, and Integrate Data
4. Analysis/Modelling - Develop and validate predictive or descriptive models
5. Validation - Assess performance of the models if they meet project objective
6. Visualization/Presentation - Present results to stakeholders using charts, diagrams e.t.c

BUSINESS PROBLEMS
i. What is the average transaction amount by location and transaction type?
ii. Which ATM location has the highest number of transactions per day, and at what time of the day do the transactions occur most frequently?
iii. Which age group has the highest number of transactions, and which transaction type do they usually perform?
iv. What is the trend of transaction volume and transaction amount over time, and are there any seasonal trends or patterns?
v. What is the most common transaction type, and how does it vary by location and customer type (Wisabi customer vs. non-Wisabi customer)?
vi. What is the average transaction amount and transaction frequency per customer by occupation and age group?
vii. What is the percentage of transactions that are withdrawals, savings, balance enquiries, and transfers, and how does it vary by location and time of day?
viii. What is the distribution of transaction amounts and transaction frequency, and are there any outliers?
ix. Which ATM locations have the highest and lowest utilization rates, and what factors contribute to this utilization rate?


Steps Taken
1. Load the transactions folder into power query
2. Clean and tranform the data. 
   Created a custom table to find the duration between the start date and time and end date time
   Created a new column to bring out the start date time in Hour
   Changed the start date time format to Date
   On the Customers table, i created a new custom column called Age
   Created a conditional column called Age group
3. Navigated to the model view to create relationships between all the tables
4. Hide the foreign key column in the transaction table (e,g Cardholder ID, Hour, TransactionTypeID e.t.c)
5. Build report to solve the  business problems using Measures and DAX expressions

![](./Wisabi_Bank.JPEG)

USEFUL INSIGHTS GOTTEN FROM THE ANALYSIS
1. The Total Amount generate by the bank is 39 Billion between the time frame of January till December 2022.
2. The Customer count duirng the time frame was 8,819.
3. The ATM Utilization rate was 12.9%
4. The Total Transaction Made during the year 2022 was 2 Million.
5. The Age group 16-25 had the highest transaction rate during the year.
6. Age group 26-35 had the highest transaction count at 394,480 in regards to Withdrawal.
7. Again the age group between 26-35 made the highest Transfer transaction at 157,809.
8. Age group 26-35 had the highest transaction count in regards to Deposits at 79613.
9. The highest agree with in regards to enquiries was once again age bracket 26-35 at 79,253.
10. From the analysis above, it has been detected that age group 26-35 are the major customers and they rank the highest in all aspects of transactions in the bank for the year 2022
