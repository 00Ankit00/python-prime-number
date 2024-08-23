# python-prime-number
#this is a python program for checking whether a number is prime or not
number=int(input("enter number: "))
composite=0
for i in range(2,number):
    if(number%i==0):
        composite+=1  
if(composite==0):
    if(number==0 or number==1):
        print("the number entered is composite")
    else:
        print("the number entered is prime")
else:
    print("the number entered is composite")
