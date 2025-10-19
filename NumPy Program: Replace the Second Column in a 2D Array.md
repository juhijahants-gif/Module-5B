#NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
Add code here
```
import numpy as np
val=eval(input())
arr=np.array(val)
print("Printing Input Array")
print(arr)
print("\nPrinting array of items in the third column from all rows")
print(arr[:,2])

```

## Output
![WhatsApp Image 2025-10-19 at 20 09 07_437f6f76](https://github.com/user-attachments/assets/eef449ba-c2e9-4e3c-b027-5750899fd220)



## Result
The program successfully takes a 2D NumPy array, deletes the second column (index 1), and inserts a new column at the same position.
