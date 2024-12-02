# Loan Performance Analysis
This repository contains information about the Loan Performance Analysis

# PROJECT TITLE: Data-Driven Lending: Insights From Loan Performance Analysis

[Introduction](Introduction)

[Data Description](Data-Description)

[Methodology](Methodology)

[Pivot tables](Pivot-tables)

[Visualizations](Visualizations)

[Findings](Findings)

[Recommendations](Recommendations)
 
## INTRODUCTION
Recently, there is an increase in competition across all businesses most especially in the lending sector due to the global economic meltdown. Data-driven insights have become important for making informed decisions and managing risk effectively. This analysis digs into a dataset to uncover patterns and trends that influence loan outcomes. By accessing key factors such as borrower demographics, loan characteristics, and repayment behaviours. The goal is to provide actionable insights that can make the company understand its loan portfolio, identify key risk factors and improve customer satisfaction. This analysis also highlights borrower segments that more likely to maintain a strong repayment record.

### OBJECTIVES
The goal is to provide actionable insights that can make the company;

Understand its loan portfolio 

Identify key risk factors 

Improve customer satisfaction 


### DATA DESCRIPTION
Data Overview
This loan dataset contains detailed information on a range of loans issued by a financial institution, including several categories of variables, such as borrower demographics, loan attributes, and repayment history, making it a valuable resource for understanding factors that impact loan performance.

### Key Features
#### 1. Borrower Information

• Income: The annual income reported by the borrower.

• Job Title: Job title of the borrower.

• Debt-to-Income (DTI) Ratio: A metric representing the borrower’s monthly debt payments as a percentage of their income.

#### 2. Loan Characteristics

• Loan Amount: The total amount of money borrowed.

• Loan Purpose: The stated purpose of the loan (e.g., Car, Medical, Educational, House).

• Interest Rate: The interest rate charged on the loan, which can vary based on borrower risk.

• Loan Term: The duration of the loan in months or years (e.g., 36 months, 60 months).

• Issued Date: The date the loan was issued.

#### 3. Loan Performance

• Loan Status: The current status of the loan (e.g., current, charged-off, fully paid).

•	Last Credit Pull Date: Date of the last credit pull on the borrower.

•	Last Payment Date: Date of the last payment made by the borrower.

•	Next Payment Date: Date when the next payment is due.

•	Installment	Monthly: Installment amount for the loan.
Total Payment: Total amount paid by the borrower by the end of the loan period.


## METHODOLOGY

### 1.	Data Cleaning and Preprocessing

Several data cleaning steps were undertaken to ensure accurate analysis,

• Handling Missing Values: Missing data in fields like Job title, Loan amount and Annual income were addressed through imputation.

•	Removal of duplicates: Duplicates were removed to avoid repetition of data.

• Addressing Inconsistencies: Some numeric fields were normalized to make format consistent, especially across income, interest rate, DTI and loan amount.

•	Renaming columns: Some columns were renamed to make the field easier to understand.

•	Re-arranging columns: Some columns were re-arranged to make the dataset organized

### 2.	Exploratory Data Analysis (EDA)

To uncover patterns and trends, descriptive and visual analyses were conducted:

•	Summary Statistics: Central tendency measures (mean, median) and standard deviation were computed for key variables such as annual income, interest rate, debt-to-income ratio and loan amount.

•	Data Visualization: Charts were created to analyze the distribution of loan purposes and number of loans issued. Line charts highlighted relationships between variable such as employee years length vs. creditworthiness and annual income vs number of loans issued. A map was created to visualize the distribution of loans across various states.

•	Segmentation Analysis: Borrowers were segmented by income levels and DTI ratios to identify high-risk groups.

### 3. Derived Features:

•	"Creditworthiness” was derived from the Loan Status, to identify good and bad loans.


## FINDINGS
An interactive summary dashboard was created using PivotTables and charts to visualize key findings.

•	Borrowers with higher DTI ratios were more likely to default. 

•	Those employees within the annual income band of $4,000-$114,000 have the highest number of loans issued, the highest good loans and also the highest bad loans. While the annual income band $1,874,000-$1,984,000 has the lowest number of loans issued.

•	Certain loan purposes, such as "Debt Consolidation," were associated with higher bad loans.

•	Borrowers with higher incomes tended to secure loans with lower interest rates.

•	December is the month with the highest number of loans issued.

•	Borrowers that their information were not verified has the highest bad and good loans.

•	California has the highest number of good and bad loans.



## RECOMMENDATIONS
### 1.	Address High Default Risks from Borrowers with High DTI Ratios:
    To address the high default risks, I would suggest;
   
•	Impose stricter limits on allowable DTI ratios for loan approvals. For borrowers with borderline DTI ratios, consider offering loans with shorter terms or higher interest rates to mitigate risk.

•	Track high-DTI borrowers closely post-loan issuance and provide reminders or financial counseling to help manage their repayment schedules.

3.	Mitigate Risks in "Debt Consolidation" Loans
•	Implement additional checks for borrowers seeking debt consolidation loans, as this category has higher bad loans.
•	Provide financial education to borrowers in this segment to help them manage their consolidated debts effectively.
4.	Leverage Insights from Income Band Trends
•	Since the $4,000–$114,000 income band constitutes the majority of loans (both good and bad), focus on tailored products for this group to maximize profitability while minimizing risks.
•	Develop incentives to attract borrowers in higher income bands (e.g., $1,874,000–$1,984,000), such as competitive interest rates and premium benefits, to diversify the loan portfolio.
5. Optimize Interest Rates Based on Income Levels
•	I recommend to continue to offer lower interest rates to high-income borrowers to attract low-risk profiles. 
6. Capitalize on Seasonal Trends
•	Launch targeted marketing campaigns in November and December to capture the seasonal surge in loan applications.
•	Ensure adequate staffing and resources during December to handle the peak in loan issuance efficiently.
7. Improve Verification Processes
•	Make information verification mandatory for borrowers in high-risk categories (e.g., high DTI, "Debt Consolidation" loans) to reduce default rates.
•	For good borrowers with non-verified information, consider streamlining the verification process to improve loan quality without deterring applications.
8. Target Regional Opportunities
•	Since California has the highest number of both good and bad loans, focus on offering tailored loan products specific to this market. For example:
a)	Incentivize good borrowers with rewards or rate discounts.
b)	Introduce stricter checks for high-risk profiles in this region.
•	Use insights from California's borrower data to replicate success in other regions.
