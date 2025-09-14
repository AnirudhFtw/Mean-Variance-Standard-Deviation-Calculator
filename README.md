# Mean-Variance-Standard Deviation Calculator

This project is part of the **Data Analysis with Python** certification on [freeCodeCamp](https://www.freecodecamp.org/).  
The goal is to create a function that calculates statistics (mean, variance, standard deviation, min, max, sum) on a 3x3 matrix using **NumPy**.

---

## 📌 Project Description

- The function `calculate()` takes a list of **9 numbers**.
- Converts the list into a **3x3 NumPy array**.
- Returns a dictionary containing the **mean, variance, standard deviation, max, min, and sum** along:
  - **axis=0 (columns)**
  - **axis=1 (rows)**
  - **flattened matrix**

---

## 📂 Files

- `mean_var_std.py` → contains the `calculate()` function.
- `README.md` → this file.

---

## ⚙️ Usage

```python
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)
