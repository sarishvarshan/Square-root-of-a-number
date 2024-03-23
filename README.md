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
Developed by: Sarish Varshan V
RegisterNumber: 212223230196 
*/
```
def newton_method(number,iterations=100):

    for i in range(iterations):
    
        number=0.5*(number+inp/number)
        
    return number
    
inp=int(input())

print("Square root of the number:",newton_method(inp))

```

## Output:
![Screenshot 2024-03-23 110429](https://github.com/sarishvarshan/Square-root-of-a-number/assets/152167665/c633627a-bce8-402a-b220-fb3b146adfde)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
