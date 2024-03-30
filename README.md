Project Title
Easy_Calculator
Description 
The purpose of the project is to provide to the wide users a user-friendly calculator app supporting basic arthmetic operations
Features
Basic arthmetic operations (addition, substraction,multiplication, division)
User-friendy interface 
Cross-platform compatibility
How to use it
Enter a first number, then click on operator, after  enter a second number
# Easy Calculator
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
elif op == ":":
    print(num1 / num2)
else:
    print("Invalid operator")
