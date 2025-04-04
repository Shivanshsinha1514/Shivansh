# Shivansh
**#Assignment:3**
#Task:1
n=int(input("Enter a number"))
def factorial(n):
    if n<2:
        return 1
    else:
        return n * (factorial(n-1))
ans= factorial(n)
print("Factorial of ",n,"is",ans)

#Task:2
a = int(input("Enter a number:"))
from math import *
b= sqrt(a)
c = log(a,e)
d= sin(a)
print("Square root:",b)
print("Logarithm:",c)
print("Sine:",d)
