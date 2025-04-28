## Experiment No: 1d – Conditional Statements

## AIM  

Write a python program to check whether the given number is even or odd using If..else statements.

## ALGORITHM

Start

Input an integer number from the user.

Check if number % 2 == 0:

If yes, then the number is Even.

If no, then the number is Odd.

Output "EVEN" or "ODD" based on the check.

End

## PROGRAM
```
def check_even_odd(number):
    if number % 2 == 0:
        return "EVEN"
    else:
        return "ODD"

# Input from the user
number = int(input())

# Check and print whether the number is even or odd
result = check_even_odd(number)
print(result)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/763057f0-7c88-453b-b638-fd83ea03f4fb)

## RESULT
Thus the python program for checking the given number is even or odd using If..else statements is successfully verified.
