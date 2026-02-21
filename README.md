# Employee-Success-Analytics-at-NextGen-Corp.
# 1.1 Overview
NextGen Corp. is a growing technology company focused on developing innovative solutions in the software
and hardware spaces. The company prides itself on attracting top talent and maintaining high employee
satisfaction to drive growth. However, there are increasing concerns regarding employee turnover,
performance variability, and salary disparities within departments.
# 1.2 Aim of the Project
To ensure continued success, NextGen Corp. needs to optimize employee retention, track employee
performance consistently, and maintain fair salary structures across departments. The HR department needs a
data-driven approach to:
- Identify trends and patterns in employee retention and turnover.
- Track and evaluate performance across different departments.
- Assess the relationship between salary and performance to ensure fairness and employee satisfaction.
# 1.3 Data Description
- #### Employees Table:  
Contains essential employee details
like name, job title, hire date, salary, performance score,
attendance rate, and department affiliation.
- #### Departments Table: 
Contains the list of departments
within NextGen Corp. (e.g., Engineering, Sales, HR,
Marketing).
- #### Performance Table:
Tracks monthly performance
scores of employees, allowing you to analyze performance
trends over time.
- #### Attendance Table: 
Tracks attendance records for
employees, including whether they were present or absent.
- #### Turnover Table: 
Contains data on employees who left
the company, including the reason for leaving.
- #### Salaries Table:
Provides salary data, including historical
salary changes for each employee.
# 2.Analysis
## 2.1 Problem Statement
NextGen Corp. is experiencing growing challenges related to employee turnover, inconsistent performance levels, and potential salary disparities across departments, which may impact organisational stability and long-term growth. While the company has access to structured HR data across employees, performance, attendance, turnover, and compensation, it currently lacks a unified, data-driven framework to identify retention risks, evaluate departmental performance trends, and assess pay equity in relation to performance outcomes. To support strategic workforce planning and sustainable growth, there is a need to analyse employee lifecycle data within a centralised PostgreSQL database to uncover patterns in attrition, measure performance variability, and evaluate salary fairness across roles and departments. The objective of this project is to generate actionable insights that enable HR leadership to strengthen retention strategies, improve performance management practices, and ensure equitable and performance-aligned compensation structures.
# 3. Database Queries and Out-Put
## 3.1 Employee Retention Analysis
- ## Goal: Understand the employee turnover trends and identify the root causes of high turnover rates.
### i. Who are the top 5 highest serving employees?

<img src="https://github.com/user-attachments/assets/005b6645-7469-4679-ac73-05c909117a0a" width="100%" alt="Screenshot 2026-02-21 105438" />

### ii. What is the turnover rate for each department?

<img src="https://github.com/user-attachments/assets/3b63be23-6934-451d-b52a-7c3a60a33c37" width="100%" alt="Screenshot 2026-02-21 110329" />

### iii. Which employees are at risk of leaving based on their performance?

<img src="https://github.com/user-attachments/assets/81790f5d-a786-4047-ac3b-c93262980e86" width="100%" alt="Screenshot 2026-02-21 125900" />

### iv. What are the main reasons employees are leaving the company?

<img src="https://github.com/user-attachments/assets/123fe197-dcd2-4dc0-bb44-d76482abd917"  width="100%" alt="Screenshot 2026-02-21 130145" />

## 3.2 Performance Analysis
- ## Goal: Evaluate employee performance across different departments and identify areas where performance can be improved.
### i.How many employees has left the company?

<img src="https://github.com/user-attachments/assets/1e3bedf1-8563-4290-ba7f-04812ea4ac9f" width="100%" alt="Screenshot 2026-02-21 130855" />

### ii.How many employees have a performance score of 5.0 / below 3.5?

<img src="https://github.com/user-attachments/assets/40414a7e-f28e-4803-9f9e-e537e40d5ac2" width="100%" alt="Screenshot 2026-02-21 131149" />

### iii.Which department has the most employees with a performance of 5.0 / below 3.5?

<img src="https://github.com/user-attachments/assets/8d20ef82-ab2f-4996-ae7a-4f7ad89a45f5" width="100%" alt="Screenshot 2026-02-21 131613" />

### iv.What is the average performance score by department?

<img src="https://github.com/user-attachments/assets/23358c0a-4465-4b9a-9b7e-2766e8cdb496"  width="100%" alt="Screenshot 2026-02-21 132727" />

















