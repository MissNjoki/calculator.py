num1=float((input("Enter the first number: ")))
num2=float((input("Enter the second number: ")))
operation=input("Enter the operation you want to perform: ")
if operation=="+":
   result=num1+num2
elif operation=="-":
    result=num1-num2
elif operation=="*":
    result=num1*num2
elif operation=="/":
    result=num1/num2
else:
    print("Invalid operation")

print("result is:", num1, operation, num2, "=", str(result))# calculator.py
