# If-Else-Assignment
marks = float(input("enter your marks:"))
if marks>90:
    print("A grade")
elif marks>80 and marks<=90:
    print("B grade")
elif marks>60 and marks<=80:
    print("C grade")
elif marks<60:
    print("d grade")
else:
    print("you are failed")

salary=int(input("enter your salary"))
time=int(input("enter your time period of service"))
if time>10:
    print("Your bonus is=",salary*10/100)
elif time<=10 and time>=6:
    print("Your bonus is=",salary*8/100)
elif time<6:
    print("Your bonus is=",salary*6/100)

price=int(input("enter the price of the good"))
if price>10000:
    print("your final price=",price-(price*20/100))
elif price>7000 and price<=10000:
    print("your final price=",price-(price*15/100))
elif price>=7000:
    print("your final price=",price-(price*10/100))

e=int(input("Enter english marks:"))
m=int(input("Enter maths marks:"))
s=int(input("Enter science marks:"))
sc=int(input("Enter social science marks:"))
if e>80 and m>80 and s>80 and sc>80:
       print("Congratulations, You got science stream!!")
elif e>80 and m>50 and s>50:
       print("Congratulations, You got commerce stream!!")
elif e>80 and sc>80:
        print("Congratulations, You got humanities stream!!")

a=int(input("enter the number"))
if (a%5)==0:
    print("hello")
else:
    print("bye")
