# Prediction Of Employee Attrition

## Objective
Prediction Of Employee Attrition using Python

## Data Description
This data set consists of 14999 observations and 10 variables. Each row in dataset represents an employee; each column contains employee attributes:

* satisfaction_level: It is employee satisfaction point, which ranges from 0-1.
* last_evaluation: It is evaluated performance by the employer, which also ranges from 0-1.
* number_projects: How many numbers of projects assigned to an employee.
* average_monthly_hours: How many average numbers of hours worked by an employee in a month.
* time_spent_company: time_spent_company means employee experience. The number of years spent by an employee in the company.
* work_accident: Whether an employee has had a work accident or not.
* promotion_last_5years: Whether an employee has had a promotion in the last 5 years or not.
* Departments: Employee's working department/division.
* Salary: Salary level of the employee such as low, medium and high.
* left: Whether the employee has left the company or not.

## Conclusion
* We got a classification rate of 97%, considered as good accuracy.
* Precision: In my prediction case, when Gradient Boosting model predicted an employee is going to leave, that employee actually left 95% of the time.
* Recall: If there is an employee who left present in the test set then my Gradient Boosting model can identify it 92% of the time.

* Exploratory data analysis and visualization of employee attrition dataset using matplotlib and seaborn. 
* Model building and evaluation using python scikit-learn package.
