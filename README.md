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
#program to find the square root for the given number(newton's method) using function.
#Developed by:Anbuselvan.S
#Reg No:23005959
def square_root(a):
    x=0.5*a
    y=0.5*(x+a/x)
    while y!=x:
        x=y
        y=0.5*(x+a/x)
    return x
n=int(input())  
result=square_root(n)
print("Square root of the number:",result)
```

## Output:
![image](https://github.com/anbuselvan1519/Square-root-of-a-number/assets/139841744/0cc671fd-0b35-414b-8e73-d84fe3a72cec)

## Result:
Thus the program to find the square root of a numberis written and verified using python programming



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
