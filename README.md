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
print(result)