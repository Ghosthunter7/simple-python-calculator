# simple-python-calculator

def calculator():
    print("Simple Calculator (CLC)")
    print("Operations: +, -, *, /, ** (power), % (modulus)")
    
    try:
        num1 = float(input("Enter first number: "))
        operator = input("Enter operator: ")
        num2 = float(input("Enter second number: "))

        if operator == "+":
            result = num1 + num2
        elif operator == "-":
            result = num1 - num2
        elif operator == "*":
            result = num1 * num2
        elif operator == "/":
            result = num1 / num2 if num2 != 0 else "Error: Division by zero"
        elif operator == "**":
            result = num1 ** num2
        elif operator == "%":
            result = num1 % num2
        else:
            result = "Invalid operator"

        print("Result:", result)
    except ValueError:
        print("Invalid input! Please enter numbers.")

calculator()
