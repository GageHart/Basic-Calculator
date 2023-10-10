# Basic-Calculator
This is a basic calculator written in Python allowing the user to input 2 numbers (numbers can be whole numbers or decimals) and then add, subtract, multiply, and divide. 


num1 = float(input("Enter first number: "))
op = input("Enter operator: ")
num2 = float(input("Enter second number: "))

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "/":
    print(num1 / num2)
elif op == "*":
    print(num1 * num2)
else:
    print("invalid operator")
