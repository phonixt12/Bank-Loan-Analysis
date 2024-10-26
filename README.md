
# Table Of Content
[Project Overview](#project-overview)<br>
[Project Object](#project-Object)<br>
[Data Source](#Data-Source)<br>
[Methodology](#Methodology)<br>
[Key Insights and Findings](#Key-Insights-and-Findings)<br>
[Tools and Technologies](#Tools-and-Technologies)<br>
[Principal Visualizations](#Principal-Visualizations)<br>
[Data Explanation](#Data-Explanation)<br>

---
# Project Overview


This project aim to analyze the lending operation of a bank and establish a interactive dashboard which support them in their lending operation. This project use SQL for extracting date and Powerbi for visulaization.This project aims to enhance data depth and interactivity, enabling stakeholders to extract meaningful insights for informed decision-making and to fully leverage the potential of bank's loan data

---
# Project Object

Report bank's lending progress in a year for stakeholders
Provide specific view about lending operation in different aspects 
Support bank in evaluating the target customer, potential customer and key location.
Have a close look in final health of bank like : Total Funded Amount, Average Interest Rate, and Loan Status metrics

---
# Data Source

The data of this project is taked from the Internet. This is the link of the datasource : [link](https://github.com/phonixt12/Bank-Loan-Analysis/tree/main/data%20source)

---
# Methodology

The project aim to analyze the data source and give an actionable insights which support the bank in decision making

**Data Analysis and SQL Queries:** <br>
**Objective:** This step extract the data for analyzing which give insights, and KPI indicator. <br>
**Process:** SQL queries were used to extract important KPI as : total and monthly loan applications, funded amounts, and average interest rates. It will give an specific view about trend and lending operation

**Categorization of Loans:** <br>
**Objective:** Classify loans based on repayment performance. <br>
**Process:** Shows the distribution between good and bad loans and classified using KPI indices (applications, funding, payments) and presented as percentages. It support in risk assessment.


**Temporal and Categorical Analysis:** <br>
**Objective:** Examine the data across various dimensions and time frames.<br>
**Process:** Detailed analysis was conducted based on multiple factors, including issue month, state, loan term, employee length, loan purpose, and home ownership status. This multifaceted analysis enabled a comprehensive understanding of the factors influencing loan performance.


**Visualization:** <br>
**Objective:** Transform data into actionable visual insights.<br>
**Process:** The results from the SQL queries were visualized using Power BI. The visualizations was designed to ensure data consistency and to provide a clear, graphical representation of the findings. This step was critical for communicating insights effectively to stakeholders.

---
# Key Insights and Findings

**Total Loan Applications :** the total customer are lending in bank. The Month-To-Date (MTD) and Previous Month-To-Date (PMTD) metrics, providing insights into monthly application trends

**Total Funded Amount vs. Amounts Received:** those metrics will shown the bank's situation and bank revenue which support stakeholders in decison making  for future strategies.

**Average Interest Rate and DTI (Debt-to-Income Ratio):** assess the interest and DTI support bank for managing bank's health financial and customer weathy.

**Loan Categorization :** categorize data into 2 type (Good and Bad) support operation team to minimize the risk and have solution for reducing the bad loan.

**Detailed Breakdowns by Various Factors:** In-depth analysis by loan status, purpose, state, term, and other factors to identify underlying patterns and trends influencing loan performance and customer behavior

---
# Tools and Technologies Used
**MySQL Workbench :** extract, query and analysis the datasource.SQL have crucial role in extracting key metrics and trends <br>

**Power BI:** Employed for data visualization and dashboard creation. Using Power BI to create an interactive dashboards that visualize loan portfolio performance and trends.

---


# Principal Visualizations


Summary
![image](https://github.com/user-attachments/assets/67fd5f4e-16dc-4559-a3e5-bde39a3ab528)

Overview
![image](https://github.com/user-attachments/assets/dc273e5b-9189-483a-972f-adf7b94e3522)

Details

![image](https://github.com/user-attachments/assets/9543b2e8-0987-4d8e-b53f-979c2a040f0c)

---
# Data Explanation

| Field  | Purpose | Note
| ------------- | ------------- |---
| Loan ID  | A unique identifier assigned to each loan application or account.  |Efficiently oversee and monitor loans throughout their entire lifecycle, organize loan documentation, track repayment schedules, and handle customer inquiries.
| Address State  | Indicates the borrower's location.  |Analyze loan demand patterns across various regions, refine marketing strategies accordingly, and manage risk portfolios based on geographical areas
| Employee Length  |Provides insights into the borrower's employment stability.  |Evaluate a borrower's ability to repay, noting that stable employment often indicates a lower risk of default.
| Employee Title  | Specifies the borrower's occupation or job title.  |Confirm income sources, evaluate the borrower's financial capacity, and customize loan offerings for various professions
| Grade  | Represents a risk classification assigned to the loan based on creditworthiness.  |Establish loan pricing and manage risk, with higher-grade loans typically receiving lower interest rates.
| Sub Grade  | Refines the risk assessment within a grade, providing additional risk differentiation.  |Provide a more detailed risk assessment, enabling banks to customize interest rates and lending terms to align with each borrower's risk profile.
| Home Ownership  | Indicates the borrower's housing status.  |Evaluate collateral availability and borrower stability, noting that homeowners may have lower default rates.
| Issue Date  | Marks the loan's origination date.  |Monitor loan aging, calculate accrued interest, and oversee loan portfolios.
| Last Credit Pull Date  |Records when the borrower's credit report was last accessed.  |Monitor credit history updates, evaluate credit risk, and make well-informed lending decisions
| Last Payment Date  | Marks the most recent loan payment received  |Analyze payment behavior, determine delinquency rates, and forecast future payments
| Loan Status  | Indicates the current state of the loan (e.g., fully paid, current, default)  |Monitor loan performance, classify loans for risk evaluation, and determine necessary provisioning requirements
| Next Payment Date  | Estimates the date of the next loan payment  |Facilitate cash flow forecasting, manage liquidity planning, and project revenue from loan portfolios
| Purpose  | Specifies the reason for the loan (e.g., debt consolidation, education)  |Segment and personalize loan offerings, aligning loan terms with borrowers' specific needs
| Term  | Defines the duration of the loan in months  |Structure loan agreements, compute interest payments, and manage loan maturities
| Verification Status  | Indicates whether the borrower's financial information has been verified  |Assess data reliability, verify income, and evaluate the credibility of loan applications
| Annual Income  | Reflects the borrower's total yearly earnings  |Determine loan eligibility, calculate debt-to-income ratios, and assess creditworthiness
| DTI (Debt-to-Income Ratio)  | Measures the borrower's debt burden relative to income  |Evaluate a borrower's capacity to handle loan payments and make responsible lending decisions
| Installment  | The fixed monthly payment amount for loan repayment, including principal and interest  |Formulate loan terms, calculate amortization schedules, and assess payment affordability
| Interest Rate  | Represents the annual cost of borrowing expressed as a percentage  |Price loans, maintain profit margins, and attract investors
| Loan Amount  | The total borrowed sum, defining the principal amount  |Decide on loan amounts and manage financial exposure
