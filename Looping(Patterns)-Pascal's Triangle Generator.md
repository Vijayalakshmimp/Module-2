# 🔺  Looping(Patterns)-Right angled triangle pattern of numbers in Python

This project demonstrates a simple Python program to generate Right anglesd Triangle pattern of numbers, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates Right angled Triangle using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows n from the user.
3. Loop i from 1 to n-1 (since the program uses range(1, n)):
   -Initialize num = 1 at the start of each row.
   -Loop j from n down to 1:
     -If j > i: print a space " " (to align the numbers properly).
     -Else: print the current value of num and increment num by 1.
   -After finishing the inner loop, print a newline to move to the next row.
4. Repeat until all rows are printed.
5. End the program.

---

## 🧪 Program
n=int(input())

for i in range(1,n): 

    num=1 for j in range(n,0,-1): 
        if j>i: 
            print(" ",end=' ') 
        else: 
            print(num,end=' ') num+=1 print("")

## Sample Output
<img width="1226" height="773" alt="image" src="https://github.com/user-attachments/assets/8f224d52-daa5-490a-84c8-1c29a52a2482" />


## Result
Thus the  Python program that generates Right angled Triangle using numbers. The number of rows is accepted from the user is executed and verified successfully.

