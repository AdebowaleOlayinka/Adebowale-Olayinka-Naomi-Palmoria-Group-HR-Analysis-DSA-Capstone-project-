# Palmoria Group Analysis and Workforce Report
## Project Overview 
This project involves the analysis of Palmoria Group employees Data set to uncover the insight on staff population and identify gender pay gap with the organization.The report is to be visualized using power BI to gain insight on employee demographics, salary structure and more.
## Business Problem 
Palmoria Group is facing issues on gender inequality in its three regions located in kaduna, Abuja and Lagos. The media published an headline news titled **Palmoria the Manufacturing Patriarchy** describing palmoria operating in patriarchy system. The organization is willing to address the gender disparity which is not good for the business based on the ambition to scale to other regions and even oversee
## Project Objectives
- Identify key areas within the business that gives rise to the issues
- Extract insight revealing if there is a gender pay gap among the workforce and identify the department and region that Will be the focus of the management
- Analysis the salary structure of employee Based on gender and check point out if the company meet the adopted minimum of 90k pay to employee
- Allocating bonuses to employee based on performance ratings 
## Data Description 
The project contains two data set 
- The employee data set containing 1,016 rows and columns
- Bonus rules containing thr rules for making payments to employee based on thier performance and department
## My Approach 
- **Data cleaning and Transformation**: I extracted and load the data into power BI query editor to carry out the following steps:
1. The Gender column contains male, female and blank cells. I replaced the blank cells with unspecified gender
2. The salary column had blank spaces which was passed to my knowledge that they were not longer working for the organization so i removed them reducing the row to 972
3. The department column had several NULL, i removed the Null reducing the column to 946 rows
4. Checked for duplicate and found 3 duplicates which I removed to get a remaining total of 943 unique rows
- **Added new columns**: I created a column column called salary range using a conditional statement to group the employee salary eg 10,000- 20,000, 20,000-30,000 etc
- **Merged Tables**
I was able to create a merged table by joining the employee table and bonus rules with the unique identifier which is the department and ratings columns

## Findings
- **Gender Distribution**:Palmoria Group has a total number of 943 active employee in the organization which is splitted into 464 Male, 440 Female and 39 undisclosed Gender
- **Gender distribution by Department**: Out of 12 department legal, Accounting and support was seen to have more male employees while Research and Development and service department had more females
- **Gender by Region**: Among the three main region Kaduna had over 333 employee(male= 182 and Female= 164) showing more male in the region and Lagos has the least of employee 124 male and 118 female
- **Performance Ratings by Gender**: In the performance ratings for Good and very good the female performed better than the male which reflected in higher bonus amount.
- **Salary Structure**: On an average salary the male earn more than the female in most regions and department
- **Minimum Salary compliance**: The minimum salary compliance is 90k and 292 out of out 943 employee earned below the minimum salary requirement. This indicates that palmoria group did not meet up with the requirements
- **Gender pay gap Analysis**: The overall gender pay gap is approximately 4% and it varies among each department and region. on an average salary earn approximately 4% lesser than the male
The table shows the gender pay gap across each department

| Department| Gender pay gap| Comments|
|----|---|---|
| Business Development| 9.0%| male earn more|
| Engineering| -11.05%| Female earn more|
|Human resources | 9.78%| Male earn more|
| Service|8.03%| Male earn more|

- **Allocation of Bonus and total payout(Salary+ Bonuses)**: The total bonus amount is 2.19M and the total payout is over 71M which is to be allocated to each employee across each department
- **Pay out by Region**:
- kaduna= 27M
- Abuja = 25M
- Lagos= 20M

![palmoria](https://github.com/user-attachments/assets/71648aa8-dbe5-461e-99ca-917f1e6f67b5)

![palmoria 2](https://github.com/user-attachments/assets/bd920115-bba0-4488-88d3-be88941a6f60)

 You can interact with the dashboard [Click](https://app.powerbi.com/view?r=eyJrIjoiZThhYTk3ZWUtYTRkMC00ZjA5LTljZWQtNzQ2MGM2MTYzYTk3IiwidCI6IjUzYjJmMWM0LWNiNjItNDc2MC04OTgyLWU4NGJmMDMwNmM4MiJ9)
## Recommendations 
- Ensure employee in similar role and performance level are compensated fairly regardless of the gender
- The salary should be reviewed to ensure minimum salary requirements is met
