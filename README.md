# Banking-Portfolio
## Table of Contents
   - [Project Description](#project-description)
   - [Aim of the project analysis](#aim-of-the-project-analysis)
   - [Processes](#processes)
   - [Insights](#insights)

## Project Description
Analyze banking data to derive insights into customer transactions, account details, branch performance, and customer demographics using Power BI, with a focus on robust data modeling across four datasets
<img width="1544" height="765" alt="Screenshot 2025-09-13 215859" src="https://github.com/user-attachments/assets/cd76835b-4fb0-4fb8-a909-d9e85f129f4b" />

### Aim of the project analysis
The primary objective of this project are as follows:
- Identify which region has the highest average account balance, and what is the value?
- Identify which customer has the highest net transaction amount, and what is their account type?
- Calculate how many transactions are there? And which occupation has the most transactions?

### Processes
  
- Step 1: Data Modeling
  Tools: PowerBI Data Model, DAX
  * Defined relationships between tables(Transactions, Accounts, Branches, Customers)
  * Created measures using DAX for key KPIs like Total Transaction Amount, Average Account Balance by Region, Net Transaction Amount per Customer and Transaction Count by Occupation.

- Step 2: Analysis and Dashboard Creation
  Tools: Power BI Visualization
  * Built interactive dashboards with filters, slicers and drill-through functionality.
  * Used Bar Chart: Show Total Transaction Amount by Transaction Type (Deposit vs. Withdrawal), Table: Display Region, BranchName, Average Account Balance, and Transaction Count.
  * Created KPI Cards: Total Transaction Amount, Average Account Balance by Region, Net Transaction Amount per Customer and Transaction Count by Occupation.
    
### Insights
  - Identify which region has the highest average account balance, and what is the value?
       According to average account balance by region pie chart, West region has the highest average account balance. The value is $6.29K.
    
      <img width="441" height="356" alt="Screenshot 2025-09-14 170006" src="https://github.com/user-attachments/assets/b35cbced-544b-4ab9-85de-ed7e55fbc793" />

  - Identify which customer has the highest net transaction amount, and what is their account type?
      Customer ID C011, C027 and C043 has high net transaction amount which is $50000 and account type is savings for all 3 customers.
       <img width="388" height="493" alt="Screenshot 2025-09-14 170539" src="https://github.com/user-attachments/assets/38f3ef71-c8b4-4fa9-ad60-d787281baffe" />
  
  - Calculate how many transactions are there? And which occupation has the most transactions?
     Total transaction count is 500. Engineer and Teacher occupation has the most transaction count.
    
      <img width="422" height="374" alt="Screenshot 2025-09-14 170141" src="https://github.com/user-attachments/assets/3eb6498b-1a5f-48c0-89dc-426b2c462440" />

#### Note
    Check the files section for the Power BI file and datasets
