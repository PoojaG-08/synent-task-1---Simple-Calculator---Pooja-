# Simple CLI Calculator

print("===== Simple Calculator =====")

try:
    # Taking user input
    num1 = float(input("Enter first number: "))
    operator = input("Enter operator (+, -, *, /): ")
    num2 = float(input("Enter second number: "))

    # Performing operations
    if operator == "+":
        result = num1 + num2
        print("Result:", result)

    elif operator == "-":
        result = num1 - num2
        print("Result:", result)

    elif operator == "*":
        result = num1 * num2
        print("Result:", result)

    elif operator == "/":
        if num2 == 0:
            print("Error: Division by zero is not allowed.")
        else:
            result = num1 / num2
            print("Result:", result)

    else:
        print("Invalid operator entered.")

# Handling invalid inputs
except ValueError:
    print("Error: Please enter valid numbers.")