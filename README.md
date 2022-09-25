# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
#Program to to find the square root for the given number(newton's method) using function.
#Developed by: prakash
#RegisterNumber:  22004108
x=1
n1=int(input())
for i in range(100):
    x=0.5*(x+n1/x)
print("Square root of the number:",x)
```

## Output:
![gcd of two number](/OP.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
