# Iteration Statements-The sum of series 1^2+2^2+3^2...+N^2.


## 🎯 Aim
To write a Python program that calculates the sum of the series 
1
2
+
2
2
+
3
2
+
⋯
+
𝑁
2
1 
2
 +2 
2
 +3 
2
 +⋯+N 
2
  for a given positive integer 
𝑁
N.

## 🧠 Algorithm :
1.Start the program.

2.Prompt the user to enter a positive integer 
𝑁
N.

3.Initialize a variable sum_of_squares to 0.

4.Loop from 1 to 
𝑁
N (inclusive).

For each iteration, compute the square of the current number and add it to sum_of_squares.

5.After the loop ends, print the value of sum_of_squares.

6.End the program.


## 🧾 Program :
```.py
a=int(input())
list1=[]
for i in range (1,a+1):
    mul=i**2
    list1.append(mul)
sum=0
for j in list1:
    sum+=j
print(f"The sum of the series =  {sum}")
```

## Output :
![image](https://github.com/user-attachments/assets/2fd1d2b7-05ad-4831-a360-135c0369ac58)


## Result :
The program successfully calculates and displays the sum of the series 
1
2
+
2
2
+
⋯
+
𝑁
2
1 
2
 +2 
2
 +⋯+N 
2
  based on the user's input.
