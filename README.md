# test-repo
practice
#python program to swap the values of 2 variables
x=int(input("Enter the value of 1st variable="))
y=int(input("Enter the value of 2nd variable="))
temp=x
x=y
y=temp
print("The swapped value of 1st variable=")
print("The swapped value of 2nd variable=")

#circulate the values of n variables
n1=[11,22,33,44,55]
n=int(input("Enter the number of positions to rotate="))
n1=n1[n:] + n1[:n]
print("After circulating the values=" ,n1)

#calculate the distance between 2 points
x1,y1=float(input("Enter the coordinate=")),float(input("Enter the coordinate="))
x2,y2=float(input("Enter the coordinate=")),float(input("Enter the coordinate="))
d=((x2-x1)**2+(y2-y1)**2)**0.5
print("The distance between 2 points=" ,d)

#determine if a student is eligible for examination or not based on attendance percentage
a=int(input("Enter attendance percentage"))
if a>=75:
  print("You are eligible")
elif a>=60 & a<75:
  print("Guardian call")
else:
  print("Not eligible")

#print first 100 integers backwards
for i in range(100,0,-1)
print(i)

#perform the sum of n natural numbers
n=int(input("Enter the value="))
sum=0
for i in range(0,n,1):
  sum +=i
print(sum)

#calculate the factorial of a number
fact=1
i=1
n=int(input("Enter the number="))
for i in range (1,n+1):
  fact=fact*i
print(fact)

#find out if a number is prime or not
n=int(input("Enter a number="))
for i in range(2,n):
  if n&i==0:
    print("Number is composite")
  else:
    print("Number is prime=")

  #permutation combination
  for i in range(1,4):
    for j in range(1,4):
      for k in range(1,4):
        if i!=j & j!=k & k!=i:
          print(i,j,k)

#find square root using function
def abc():
  a=int(input("Enter the value="))
  s=a**0.5
  print(s)
abc()

#find gcd using function
def gcd():
  a=int(input("Enter a value="))
  b=int(input("Enter a value="))
  while b!=0:
    a,b=b,a%b
  return a
gcd()

#factorial using nested function
def ab():
    def cd(x):
      fact=1
      for i in range(1,x+1):
          fact=fact+1
      print(fact)
    cd(5)
ab()

#print the fibonacci series using function
def fibonacci (n):
  if n<=0:
    return "Invalid input"
  elif n==1:
    return 0
  elif n==2
    return 1
  else:
    return fibonacci(n-1)+fibonacci(n-2)
  n=int(input("Enter the number upto which the sequence will be printed="))
  for i in range(1,n+1):
    print(fibonacci(i),end=",")

#find the exponentiation of a number using function
def ex():
  a=int(input("Enter the value="))
  b=int(input("Enter a value="))
  x=a**b
  print(x)
ex()





