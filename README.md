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
#Developed By : ROSHINI S
#Register Number : 212223240142


def square_root_newton_method(number):
    guess=number/2.0
    while True:
        new_guess=0.5*(guess+number/guess)
        if abs(new_guess-guess)<1e-10:
            return new_guess
        guess=new_guess
input_number=float(input())
result=square_root_newton_method(input_number)
print(f"Square root of the number: {result}")

```

## Output:

![image](https://github.com/Roshini2201/Square-root-of-a-number/assets/154105318/1f0936a8-9d59-48fa-8061-6e9728d28d7c)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
