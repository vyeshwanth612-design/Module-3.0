# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```py


import re

l1 = []


items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']


for i in items:
    if not re.search(r'e', i):
        l1.append(i)

print("Filtered list:", l1)
```
## Output
<img width="495" height="355" alt="image" src="https://github.com/user-attachments/assets/403c86e7-93ca-42bd-92c3-f0617a85276d" />


## Result
The Python program was executed successfully, and the elements that do not contain the letter 'e' were filtered using regular expressions. The filtered list was displayed correctly.
