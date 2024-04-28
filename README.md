n=int(input("enter the first number:"))
operation=input("choose the like(+,-,*,//,^):")
m=int(input("enter the second number:"))
if(operation == '+'):
    result= n + m
elif(operation == '-'):
    result= n - m
elif(operation == '*'):
    result= n * m
elif(operation == '//'):
    if(m != 0):
      result= n // m
    else:
        result="infinity"  
elif(operation == '^'):
    result= n ** m  
else:
    result= "invalid operation"  

print(f"the result of {n} {operation} {m} is: {result}")
