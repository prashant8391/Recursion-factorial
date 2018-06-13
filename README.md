# Recursion-factorial
# Code for factorial using recursion
def fact(n):
    if (n<=1):
        return 1
    else:
        return n*fact(n-1)

a=fact(5)
print("The factorial of n is:",a)
