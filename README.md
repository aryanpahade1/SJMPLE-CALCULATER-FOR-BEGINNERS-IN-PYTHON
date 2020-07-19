# SJMPLE-CALCULATER-FOR-BEGINNERS-IN-PYTHON
#num1 and num for input and int is for converting str to int
num1=int(input("Enter your first number\n"))
num2=int(input("Enter your second number\n"))
choice = input("Enter\n 1 for addition\n 2 for subtraction\n 3 for multiplication\n 4 for division\n ")
if(choice=="1"):
	print(num1+num2)
elif(choice=="2"):
	print(num1-num2)
elif(choice=="3"):
	print(num1*num2)
elif(choice=="4"):
	print(num1/num2)
