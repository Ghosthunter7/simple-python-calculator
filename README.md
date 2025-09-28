def calculator():
    operator = input("Choose operator (+, -, *, /): ")
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    if operator == '+':
        result = num1 + num2
    elif operator == '-':
        result = num1 - num2
    elif operator == '*':
        result = num1 * num2
    elif operator == '/':
        if num2 == 0:
            print("Error: Cannot divide by zero!")
            return
        result = num1 / num2
    else:
        print("Invalid operator!")
        return

    print("Result:", result)


calculator()
 
