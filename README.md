# simple-python-calculator

def calculator():
    operator = input("choose operator (+, -, *, /): ")
    num1 = float(input("choose first number: -"))
    num2 = float(input("choose second number : -"))


    if operator == '+':
      result = num1 + num2

    elif  operator == '-':
      result = num1 - num2

    elif  operator == '*':
      result = num1 * num2 

    elif operator == '/':
      result = num1 / num2  
   
    else:
     print("cant dived by zero")
  



    print("Result", result)




calculator()    

 
