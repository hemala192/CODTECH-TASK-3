CODTECH-TASK-3
Employee Attrition Prediction (Simple Rule-Based)

print("EMPLOYEE ATTRITION PREDICTION")

age = int(input("Enter employee age: "))
salary = int(input("Enter monthly salary: "))
years = int(input("Enter years of experience in company: "))
satisfaction = int(input("Enter job satisfaction (1-10): "))

# Simple prediction logic
if salary < 20000 or years < 2 or satisfaction < 5:
    result = "Employee may leave the company"
else:
    result = "Employee is likely to stay"

print("\nPrediction Result:")
print(result)Employee Attrition Prediction
 
DESCRIPTION:

Objective:

The objective of this project is to predict whether an employee is likely to stay in the company or leave based on factors such as salary, years of experience, and job satisfaction.

Key Activities:

Collect employee details as input.

Analyze factors affecting employee attrition.

Apply conditional logic to predict employee status.

Display the prediction result as "Likely to Stay" or "May Leave".


Technologies Used:

Programming Language: Python

Concepts: Variables, Input/Output Operations, Conditional Statements (if-else)

Platform: Pydroid 3 / Python Environment


Output:

The program executes successfully and displays the employee attrition prediction based on the entered employee details.