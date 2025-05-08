# Salaries of San Francisco Employee Project
* **Project Title:** Salaries of San Francisco Employee(312882 data)**
* **Database:** salaries_employees

**Project Structure**
## Database Setup
**Database Creation:** A database named salaries_employees.
**Table Creation:** A table named 'salaries' is created to store Salaries of San Francisco Employee data.

## Project Overview
* 1.Top 10 Highest Paid Employees
* 2.Average BasePay by Job Title
* 3.Total Overtime Pay by Year
* 4.Count of Employees per Year
* 5.Top 10 Job Titles with Highest Average TotalPay
* 6.Employees with Zero BasePay but Positive Pay
* 7.Job Titles with Highest Number of Employees
* 8.Average TotalPayBenefits by Year
* 9.TotalPay vs TotalPayBenefits Gap
* 10.Null or Missing Data Check

```sql
CREATE TABLE salaries(
EmployeeName VARCHAR(50),
JobTitle VARCHAR(50),
BasePay FLOAT,
OvertimePay FLOAT,
OtherPay FLOAT,
Benefits FLOAT,
TotalPay FLOAT,
TotalPayBenefits FLOAT,
Year YEAR
);
```



