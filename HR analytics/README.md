# HR Analytics Project

## Overview

This project focuses on HR analytics, leveraging SQL for data analysis. The primary datasets analyzed are the **Employee table** and the **Performance Review table**.

## Employee Table

The **Employee table** is structured to capture essential information about each employee within the organization. Here are the key attributes included in the **Employee table**:

- **EmployeeID:** Unique identifier for each employee.
- **FirstName:** First name of the employee.
- **LastName:** Last name of the employee.
- **Department:** The department in which the employee works (e.g., Sales, HR, Finance).
- **Position:** The employee's job position within the organization.
- **Age:** Age of the employee.
- **Gender:** Gender of the employee.
- **Salary:** The employee's salary.
- **YearsExperience:** Number of years of experience the employee has.

## Performance Review Table

The **Performance Review table** tracks the performance reviews conducted for each employee. It includes the following attributes:

- **ReviewID:** Unique identifier for each performance review.
- **EmployeeID:** The EmployeeID of the employee being reviewed.
- **ReviewDate:** Date when the performance review was conducted.
- **Rating:** Numeric rating assigned to the employee's performance (typically on a scale from 1 to 5).
- **Feedback:** Feedback provided during the performance review.

## How HR Analytics Can Be Helpful

HR analytics offers valuable insights and benefits to organizations in several ways:

1. **Talent Management:** Analyzing employee data can help HR professionals identify high-performing employees, assess skill gaps, and make informed decisions about talent development and succession planning.

2. **Retention and Engagement:** By analyzing performance review data, HR teams can identify factors that contribute to employee satisfaction and engagement. This information can be used to implement strategies to improve retention rates and enhance employee morale.

3. **Recruitment Optimization:** HR analytics can provide insights into the effectiveness of recruitment efforts, helping organizations optimize their hiring processes, target the right candidates, and reduce time-to-hire.

4. **Cost Reduction:** By analyzing workforce data, organizations can identify areas for cost reduction, such as optimizing staffing levels, identifying inefficiencies, and reducing employee turnover.

5. **Compliance and Risk Management:** Analyzing HR data can help organizations ensure compliance with labor laws and regulations, mitigate risks related to employee relations, and proactively address issues such as discrimination or harassment.

## Data Generation

To populate the **Employee** and **Performance Review** tables with sample data, a Python script was used. The sample data generation process involved randomizing attributes such as department, position, age, gender, salary, years of experience, review date, rating, and feedback.

The Python script provided below generates SQL insertion queries based on the randomized data, which can then be executed to populate the tables.

```python
# [Python code goes here](https://github.com/yajneshshetty/SQL-PROJECTS/blob/main/HR%20analytics/Dataset.ipynb)

Copyright © 2022 Yajnesh Shetty



