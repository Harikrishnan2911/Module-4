## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

# Dictionary 1
dict1 = {'a': 1, 'b': 2}

# Dictionary 2
dict2 = {'c': 3, 'd': 4}

# Merge dictionaries
merged = dict1.copy()
merged.update(dict2)

print("Merged dictionary:", merged)

## Output
<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/5b2e91c5-083d-4a71-bd15-7e17c835238b" />

## Result
