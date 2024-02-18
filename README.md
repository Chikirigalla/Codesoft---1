# Codesoft---1
num1 = int(input("Enter the First Number: "))
num2 = int(input("Enter the Second Number: "))
print("Enter you Choice of Operation")
print("1.ADD")
print("2.SUBTRACT")
print("3.MULTIPLY")
print("4.DIVISION")
choice=int(input())
if choice==1:
    print("Sum of two numbers is: ",num1-num2)
elif choice==2:
    print("Subraction of two numbers is: ",num1-num2)
elif choice==3:
    print("Multiplication of two numbers: ",num1*num2)
else:
    print("Division of two numbers is: ",num1/num2)
