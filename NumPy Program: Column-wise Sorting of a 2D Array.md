# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a *NumPy* program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. *Import NumPy*: Start by importing the NumPy library.
2. *Get Input*: Accept a 2D NumPy array from the user.
3. *Sort Column-wise*: Use the np.sort() function with axis=0 to sort each column in ascending order.
4. *Store Result*: Store the sorted result in a new array.
5. *Display Output*: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter the elements row-wise (space-separated):")
arr = []
for i in range(rows):
    arr.append(list(map(int, input().split())))
array = np.array(arr)
sorted_array = np.sort(array, axis=0)
print("\nOriginal Array:")
print(array)

print("\nColumn-wise Sorted Array:")
print(sorted_array)
```


## Output
<img width="556" height="324" alt="image" src="https://github.com/user-attachments/assets/71b611b1-9f43-4f95-b3ab-ef25d76c19a5" />



## Result
The program successfully accepts a 2D array from the user, sorts each column in ascending order, and prints both the original and column-wise sorted arrays using NumPy.
