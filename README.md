# Simple-Calculator
#BUILDING A BETTER CALCULATOR: 

#Enter first Number
num1 = float(input('Enter first number: '))

#Enter operator to perform
op = input('Enter operator: ')

#Enter second Number
num2 = float(input('Enter second number: '))

if op == '+':
    print(num1 + num2)
elif op == "-":
    print("The answer from calculation: ", num1 - num2)
elif op == "/":
    print("The answer from calculation: ", num1 / num2)

#Note: / stroke right is division
elif op == "*":
    print("The answer from calculation: ", num1 * num2)
else:
    print('Invalid operator')

print("Do you want to calculate again?")
