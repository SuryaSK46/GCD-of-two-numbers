# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
"""
To find the gcd of a number
Name: Surya SK
Register: 212222100052
"""
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        s=n2
    else:
        s=n1
    for i in range(1,s+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![Screenshot 2023-06-10 033650](https://github.com/SuryaSK46/GCD-of-two-numbers/assets/127716537/8c1e4999-9fd4-4c47-84a6-2b0806457175)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
