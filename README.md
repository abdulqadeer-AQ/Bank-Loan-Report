# Bank Loan Analysis
### Project Overview
This data analysis project aims to provide insights into bank loan data support risk assessment, decision-making, and portfolio management. It involves evaluating loan applications, verifying borrower information, assessing credit risk, and fraud detection to help businesses achieve their goals and manage financial needs.
### Data source
**Loan Data:** The primary dataset used for this analysis is the "financial_loan.csv" file, containing detailed information about loans made by the bank.
- Loan ID: A unique identifier assigned to each loan application
- Address State: It indicates the borrower's location
- Employee Length: It provides insights into the borrower's employment stability
- Employee Title: Borrower's occupation or job title
- Grade: It represents a risk classification assigned to the loan based on creditworthiness
- Sub Grade: It refines the risk assessment within a grade, providing additional risk differentiation
- Home Ownership: It indicates the borrower's housing status
- Issue Date: loan's origination date
- Last Credit Pull Date: Borrower's credit report was last accessed
- Last Payment Date: The most recent loan payment received
-  Loan Status: Loan Status indicates the current state of the loan (e.g., fully paid, current, default) requirements.
- Next Payment Date: It Estimates the date of the next loan payment
- Purpose: Purpose specifies the reason for the loan (e.g., debt consolidation, education).  
- Term: It defines the duration of the loan in months
- Verification Status: It indicates whether the borrower's financial information has been verified
- Annual Income: It reflects the borrower's total yearly earnings
- DTI (Debt-to-Income Ratio): It measures the borrower's debt burden relative to income
- Instalment: It fixed monthly payment amount for loan repayment, including principal and interest
- Interest Rate: It represents the annual cost of borrowing expressed as a percentage
- Loan Amount: Loan Amount is the total borrowed sum. It defines the principal amount.
### Tools & Technique 
- MySQL - Clean Data & Exploratory Data Analysis
- Power BI - Creating Reports & Dashboard
### Data Cleaning/Preparation
In this phase, remove or fill null data and duplicate values and prepare data for analysis
1. Data loading & inspection
2. Handling missing value
3. Remove duplicate values & outliers
4. Formatting the data
### Exploratory Data Analysis(EDA)
EDA involves exploring the statistical analysis of loan data and answering key questions such as:

- What is Loan Distribution and Overall Trends?
- Explore state-wise analysis.
- What are the most common purposes for loans?
- Explore monthly-wise analysis of applicants.
### key metrics
**Dashboard** contains three reports:
#### 1-Summary:
- Total Loan Application: There are around 38.6k applications with 4.3k month-to-date and 6.9% month-over-month growth.
- Total Funded Amount: $435.8M, with MTD of $54.0M and MoM growth of 13.0%.
- Total Amount Received: $473.1M, with MTD of $58.1M and MoM growth of 15.8%.
- Average Interest Rate: 12.05%, with MTD at 12.4% and month-over-month growth a 3.5%.
- Average Debt-to-Income Ratio (DTI): 13.33%, with MTD at 13.7% and 2.7% increase month-over-month.
- Find Good Loan Issued was 86.2% with 33.2K applications and $370.2M in funded loans.
- Explore Bad Loan Issued was 13.8% with 5.3K applications and $65.5M funded.
<img width="614" alt="summary" src="https://github.com/user-attachments/assets/343cfdf3-8f89-4367-8c64-1012d7f25b19">

#### 2-Overview:
This overview report provides a detailed overview of how loan applications vary based on time, geography, employment length, loan purpose, term, and home ownership status.
- The Line-filled graph shows loan applications increasing month by month, peaking at 4.3K in December.
- The map highlights geographic distribution. States with more loan applications are colored in darker shades.
- Employees are 10+ years old with 8.9K loan applications.
- Those with less than 1 year follow with 4.6K applications.
- Debt Consolidation dominates with 18K applications.
- Credit card refinancing follows with 5K applications.
- 73.2% of applications are for 60-month terms & 26.8% are for 36-month terms.  
<img width="613" alt="overview" src="https://github.com/user-attachments/assets/48678cd5-39ad-414b-bb7a-e27e7d927954">

#### 3-Detail:
The detailed table offers a comprehensive look at various loan purposes and their financial details, such as the funded amount, interest rate and monthly installments.

<img width="611" alt="Detail" src="https://github.com/user-attachments/assets/8ca2cf50-215d-422b-8650-d6d706ca0952">
