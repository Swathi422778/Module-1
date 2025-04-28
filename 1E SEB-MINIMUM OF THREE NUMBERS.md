# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers.

## ALGORITHM  
Start

Input three integers: a, b, and c.

Compare a with b and c:

If a is smaller than both b and c, then:

Output that a is the smallest.

Else, compare b with c:

If b is smaller than c, then:

Output that b is the smallest.

Else:

Output that c is the smallest.

End

## PROGRAM
```
a=int(input())
b=int(input())
c=int(input())
if a<b and a<c:
    print(f'''The Smallest  of the three a= {a} b= {b} c= {c} is {a}''')
elif b<c:
    print(f'''The Smallest  of the three a= {a} b= {b} c= {c} is {b}''')
    
else:
    print(f'''The Smallest  of the three a= {a} b= {b} c= {c} is {c}''')

```

## OUTPUT
![image](https://github.com/user-attachments/assets/e648059f-61d9-460e-876f-1ee097bdf7b8)

## RESULT
Thus the Python program for finding the minimum between three integer numbers is successfully done and verified.
