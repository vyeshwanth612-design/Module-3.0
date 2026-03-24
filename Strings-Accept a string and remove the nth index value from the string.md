# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```py


def remove(s, n):
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a


s = input()
n = int(input())


result = remove(s, n)

print("Modified string:", result)
```
## Output
<img width="661" height="478" alt="image" src="https://github.com/user-attachments/assets/23f7eb37-03db-4c25-bc77-8c91d03094df" />


## Result
The Python program was executed successfully, and the character at the specified index was removed from the string. The modified string was displayed correctly.
