# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program

# Create a list
lst = [10, 20, 30]

# Input index from user
index = int(input("Enter index: "))

try:
    print("Element:", lst[index])
except IndexError:
    print("Error: Index out of range")

## Output
<img width="1919" height="954" alt="image" src="https://github.com/user-attachments/assets/b889a5b8-a056-4e0a-8fe0-ef0e655ab7d2" />

## Result
