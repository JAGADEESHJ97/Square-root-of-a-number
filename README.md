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
def newton_method(number,num_iters=100):
    a = float(number)
    for i in range(num_iters):
        number = 0.5 * (number + a/number)
    return number
a = int(input())
print("Square root of the number:",newton_method(a))
Developed by: JAGADEESH J
RegisterNumber: 212223110015
```
## Output:
![Screenshot 2024-03-23 200623](https://github.com/JAGADEESHJ97/Square-root-of-a-number/assets/152129419/aac6afe2-62d7-4810-ba1d-a6e90ed1cfad)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
