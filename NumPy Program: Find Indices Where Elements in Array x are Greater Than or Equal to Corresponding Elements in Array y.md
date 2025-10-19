# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using *NumPy* that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y.

## 🧠 Algorithm
1. *Import NumPy*: Import the NumPy library.
2. *Define Arrays*: Define two NumPy arrays, x and y, with the same shape (i.e., same number of elements).
3. *Use Boolean Indexing*: 
   - x > y gives a boolean array where elements of x are greater than y.
   - x == y gives a boolean array where elements of x are equal to y.
4. *Find Indices*: Use np.where() to get the indices where the conditions x >= y are satisfied.
5. *Print Indices*: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np
x=eval(input())
y=eval(input())
a=np.array(x)
b=np.array(y)
pos=np.where(a>b)
posequal=np.where(a==b)
print(pos)
print(posequal)
```

## Output
![WhatsApp Image 2025-10-19 at 20 05 06_1015813d](https://github.com/user-attachments/assets/9f862645-3f77-4f3e-aff6-6bce60edb027)


## Result
The program successfully  finds the indices where elements in array x are greater than or equal to their corresponding elements in array y.
