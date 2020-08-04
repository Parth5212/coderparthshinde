n1=input("Enter your first number:")
n2=input("Enter your second number:")
n3=input("so what do you want  /  *  -  + :")
if n3=="+":
    print(int(n1)+ int(n2))
elif n3=="-":
    print(int(n1)-int(n2))
elif n3=="*":
    print(int(n1)*int(n2))
elif n3=="/":
    print(int(n1)/int(n2))
else:
    print("Please cheak your input ")
