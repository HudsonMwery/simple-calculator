# simple-calculator
simple calculator beginning

# Simple Calculator for Beginners

# Ask the user to enter the first number
num1 = input("Enter the first number: ")
# Ask the user to enter the second number
num2 = input("Enter the second number: ")
# Ask the user to choose an operation
operation = input("Enter an operation (+, -, *, /): ")

num1 = float(num1)
num2 = float(num2)

if operation == "+":
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == "-":
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif operation == "*":
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif operation == "/":
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("You can't divide by zero!")
else:
    print("Invalid operation. Please enter +, -, *, or /.")
