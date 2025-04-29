## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that prints an equilateral triangle pattern of stars (*), where the number of rows is provided as input by the user.

## 🧠 Algorithm
1.Accept an integer n as input from the user (number of rows).

2.Loop from 1 to n to handle each row:

3.For each row, print spaces to center-align the stars.

4.Print the stars (*), separated by spaces, according to the current row number.

5.End the program after printing the triangle.

## 🧾 Program :
```.py
a=int(input())
b=a+a-2
k=b
for i in range(1,a+1):
    for j in range(k):
        print(" ",end="")
    for j in range(i):
        print("*",end="  ")
    print()
    k-=1
```

## Output :
![image](https://github.com/user-attachments/assets/b9fe5c61-04ac-45c7-9629-ea503c2eaebd)


## Result :
The program successfully prints an equilateral triangle pattern of stars where each row has an increasing number of stars, and the stars are centered to form a symmetrical triangle.
