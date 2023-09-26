# calculator1
def cal(a,str,b):
    if str=="+":
        return a+b
    elif str=="-":
        return a-b
    elif str=="*":
        return a*b
    elif str=="/":
        return a/b
a=float(input("Enter first number: "))
b=float(input("Enter second number: "))
while 1:
    if b==0:
        print("Error,Enter Another Number")
        b=float(input("Enter second number: ")) 
    else: 
        break
c=str(input("1.+ 2.- 3.* 4./\n"))
print(cal(a,c,b))
