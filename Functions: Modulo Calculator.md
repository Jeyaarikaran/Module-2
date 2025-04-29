# Functions in Python: To define a function named "result" that accepts 2 values and return its sum, subtraction and multiplication.

## 🎯 Aim :
To write a Python program that defines a function named result which takes two numbers as input and returns their sum, difference, and product.

## 🧠 Algorithm :
1.Start the program.

2.Define a function named result that accepts two parameters (a, b).

3.Inside the function:

Calculate the sum of a and b.

Calculate the subtraction of b from a.

Calculate the multiplication of a and b.

4.Return all three values from the function.

5.In the main program:

Ask the user to input two numbers.

Call the result function with these two numbers.

Display the returned values (sum, subtraction, and multiplication).

6.End the program.

## 🧾 Program :
```.py
def result(a,b):
  sum=a+b
  sub=a-b
  mul=a*b
  print(f"Sum is {sum},Sub is {sub},&Multiply is {mul}")
a=int(input())
b=int(input())
```

## Output :
![image](https://github.com/user-attachments/assets/35eaf13b-39f6-4514-b1d1-e868bfb02132)


## Result :
The function works correctly and returns all three operations as expected.
