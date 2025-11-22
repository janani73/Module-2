# Exp.No:2d
## LOOPING PATTERNS -Reverse Number Pattern Printing in Python


### AIM  
To write a Python program that prints a reverse numeric pattern based on the number of rows entered by the user.

### ALGORITHM

```
1.Start the program.
2.Read the number of rows from the user and store it in rows.
3.Use a for loop that runs from rows down to 1.
4.For each row, set num = i.
5.Use an inner loop to print the value of num repeatedly for i times.
6.Move to the next line after printing each row.
7.End the program.
```

### PROGRAM
```
rows = int(input())
for i in range(rows,0,-1):
    num = i
    for j in range(0,i):
        print(num,end=' ')
    print("")
```

### OUTPUT
<img width="1180" height="307" alt="image" src="https://github.com/user-attachments/assets/f9cba587-bdd6-4b09-9b50-0f92e44a5cc9" />


### RESULT
The program successfully reads the number of rows and prints a reverse numeric pattern where each row displays repeated values from the highest number down to 1.
