# Fibonacci-series



num=int(input("Enter the number"))
n1,n2=0,1
sum =0
if num<=0:
  print("Please enter the valid number")
else:
  for i in range(0,num):
    n1=n2
    n2=sum
    sum=n1+n2
    print(sum)
