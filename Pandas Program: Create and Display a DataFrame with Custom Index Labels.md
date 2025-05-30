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
```
import pandas as pd
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [24, 27, 22],
    'City': ['New York', 'Los Angeles', 'Chicago']
}
custom_index = ['A1', 'B2', 'C3']
df = pd.DataFrame(data, index=custom_index)
print("DataFrame with Custom Index Labels:")
print(df)
```

## Output
![442483970-46febcfd-ff18-4c5f-82bd-3da2072d98fa](https://github.com/user-attachments/assets/05de96ed-0e80-4a9c-9d85-b4f19d5b3203)

## Result
Thus,the program has been executed successfully.
