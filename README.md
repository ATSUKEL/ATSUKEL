def calculate_take_home_salary(gross_salary, deductions):
    return gross_salary - deductions

def get_user_input(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Please enter a valid number.")

# Get user input
gross_salary = get_user_input("Enter your gross salary: ")
taxes = get_user_input("Enter total taxes: ")
other_deductions = get_user_input("Enter other deductions: ")

# Calculate total deductions
total_deductions = taxes + other_deductions

# Calculate take-home salary
take_home_salary = calculate_take_home_salary(gross_salary, total_deductions)

# Display results
print(f"\nGross Salary: ${gross_salary:.2f}")
print(f"Total Deductions: ${total_deductions:.2f}")
print(f"Take-Home Salary: ${take_home_salary:.2f}")



def get_user_input(prompt):
    # Indent the while loop to be within the function definition
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Please enter a valid number.")



# Get user input

gross_salary = get_user_input("Enter your gross salary: ")

taxes = get_user_input("Enter total taxes: ")

other_deductions = get_user_input("Enter other deductions: ")



# Calculate total deductions

total_deductions = taxes + other_deductions



# Calculate take-home salary

take_home_salary = calculate_take_home_salary(gross_salary, total_deductions)



# Display results

print(f"\nGross Salary: ${gross_salary:.2f}")

print(f"Total Deductions: ${total_deductions:.2f}")

print(f"Take-Home Salary: ${take_home_salary:.2f}")
