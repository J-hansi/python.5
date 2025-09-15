#strong/krishnamurty number'''
num= int(input("enter the number:"))
temp=num
sum_fact=0
while temp!=0:
    d= temp%10
    fact=1
    i=1
    while i<=d:
        fact *=i
        i+=1 
    sum_fact+= fact
    temp//10
if sum_fact == num:
    print("strong")
else:
    print("not")
