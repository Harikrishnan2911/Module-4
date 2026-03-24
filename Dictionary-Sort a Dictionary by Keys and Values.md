# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program

# Given dictionary
d = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

# Sort keys
sorted_keys = sorted(d.keys())

# Sort values
sorted_values = sorted(d.values())

# Output
print("Keys in alphabetical order:", sorted_keys)
print("Values in alphabetical order:", sorted_values)

## Sample Output
<img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/cfa6cb85-22e0-4798-b45d-ca11adfa08c4" />

## Result

