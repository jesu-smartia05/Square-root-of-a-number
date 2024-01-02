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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: 212223110016
RegisterNumber:  JESU SMARTRIA A

def method(number,number_iters):
  a=float(number)
  for i in range(number_iters):
    number=0.5*(number+a/number)
  return number
a=int(input())
print("Square root of the number:",method(a))
*/
```

## Output:

![Screenshot 2024-01-02 183614](https://github.com/jesu-smartia05/Square-root-of-a-number/assets/148514819/f6d4da8e-7747-44f1-a98a-e3a8531c18d6)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
