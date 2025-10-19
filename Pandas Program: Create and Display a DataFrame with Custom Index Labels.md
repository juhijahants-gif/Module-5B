# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
Add code here
```
import pandas as pd
l1=eval(input())
df=pd.DataFrame(l1)
print(df)

```

## Output
![WhatsApp Image 2025-10-19 at 20 12 08_7d3dcbb2](https://github.com/user-attachments/assets/dfcbc004-050b-44f0-b1a4-47c3fbc4961a)



## Result
The program successfully creates a Pandas DataFrame from a dictionary and applies custom index labels.
The DataFrame displays all columns (name, score, attempts, qualify) along with the specified row indices (a, b, c, d, e).
