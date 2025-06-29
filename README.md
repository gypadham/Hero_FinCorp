# Hero_FinCorp
Analyze Hero FinCorp’s loan portfolio and customer behavior to uncover default risks, branch efficiency, customer insights, and profitability—driving smarter approvals, reduced defaults, and improved operations through data-driven decisions.
**Customer Demographics**
➢ Contains details about Hero FinCorp's customers.
➢ Key Columns:
○ Customer_ID: Unique identifi er for each customer.
○ Full_Name: Name of the customer.
○ Credit_Score: Numerical credit rating of the customer.
○ Annual_Income: Yearly income of the customer.
○ Employment_Status: Employment type (e.g., Salaried, Self-Employed).
**Loan Data**
➢ Details of all active and closed loans.
➢ Key Columns:
- Loan_ID: Unique identifi er for each loan.
- Customer_ID: Customer associated with the loan.
- Loan_Amount: Principal loan amount.
- Interest_Rate: Annual interest rate on the loan.
- Loan_Term: Loan repayment duration in months.
**Loan Applications**
➢ Tracks the loan application process.
➢ Key Columns:
- Application_ID: Unique identifi er for each loan application.
- Approval_Status: Whether the application was approved or rejected.
- Rejection_Reason: Reason for rejection (if applicable).
- Processing Fee: Fee charged during the application process.
- Application_Date: Date of application submission.
**Transactions**
➢ Record all fi nancial transactions related to loans.
➢ Key Columns:
- Transaction_ID: Unique identifi er for each transaction.
- Loan_ID: Associated loan for the transaction.
- Transaction_Type: Type of transaction (e.g., EMI Payment, Penalty).
- Transaction_Amount: Monetary amount of the transaction.
- Transaction_Date: Date of the transaction.
**Default Records**
➢ Details of customers who defaulted on their loans.
➢ Key Columns:
○ Default_ID: Unique identifi er for each default case.
○ Loan_ID: Associated loan for the default.
○ Default_Amount: Amount remaining unpaid.
○ Recovery_Amount: Amount recovered post-default.
○ Default_Date: Date when the default occurred.
**Branch Information**
➢ Contains information about Hero FinCorp branches.
➢ Key Columns:
○ Branch_ID: Unique identifi er for each branch.
○ Region: Geographic location of the branch.
○ Total_Active_Loans: Number of loans currently active in the branch.
○ Delinquent_Loans: Number of overdue loans in the branch.
○ Loan_Disbursement_Amount: Total loan disbursement volume.
