# Exp.No:2b  
## FUNCTIONS - Function-Based Arithmetic Operations in Python

### AIM  
To write a Python program that uses a function to perform addition, subtraction, and multiplication on two input numbers and display the calculated results.

### ALGORITHM
```
1.Start the program.
2.Define a function result(a, b) to calculate sum, subtraction, and multiplication.
3.Inside the function, compute:
sum = a + b
sub = a - b
mul = a * b
4.Print the results inside the function.
5.Read two integers a and b from the user.
6.Call the function result(a, b) with the inputs.
7.End the program.
```
### PROGRAM
```
def result(a, b):
    sum = a+b
    sub = a-b
    mul = a*b
    print(f"Sum is {sum}, Sub is {sub}, & Multiply is {mul}")
a = int(input())
b = int(input())
result(a,b)
```
### OUTPUT
<img width="1181" height="362" alt="image" src="https://github.com/user-attachments/assets/f901b966-7074-4799-ad84-c5c050435273" />

### RESULT
The program successfully reads two integers, processes them through a user-defined function, performs arithmetic operations, and displays the sum, difference, and product correctly.
