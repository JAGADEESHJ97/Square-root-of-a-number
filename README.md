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
def gcd():
    a,b=int(input()), int (input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf =i
    print("GCD of two numbers is:",hcf)        

Developed by: JAGADEESH J
RegisterNumber: 212223110015
```

## Output:

![Screenshot 2024-03-23 092052](https://github.com/JAGADEESHJ97/Square-root-of-a-number/assets/152129419/0698c35f-6fb1-40a8-afa0-7fe1847c72c1)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
