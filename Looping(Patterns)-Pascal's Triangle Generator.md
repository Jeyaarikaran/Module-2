# 🔺 Looping(Patterns)-Pyramid Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that prints an inverted pyramid pattern using the same digit, based on user input.
---

## 🧠 Algorithm
1.Read an integer input n from the user.

2.Loop from n down to 1.

3.In each iteration, print the digit n repeated i times.

4.End the program.

---

## 🧪 Program :
```.py
a=int(input())
for i in range(a,0,-1):
    for j in range(i):
        print(a,end=" ")
    print()
```
##  Output :
![image](https://github.com/user-attachments/assets/feff0053-e6fc-46c6-8a4c-ffde595a3852)


## Result :
The program successfully prints an inverted pyramid pattern using the same input digit and matches the expected output.

