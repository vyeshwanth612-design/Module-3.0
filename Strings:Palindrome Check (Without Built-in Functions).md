# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```py

s = input()

rev = ""
for i in s:
    rev = i + rev

if s == rev:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
```
## Output
<img width="517" height="231" alt="image" src="https://github.com/user-attachments/assets/9b728f98-a0ef-4a23-940d-bd2ebce72fa5" />


## Result
The Python program was executed successfully, and the given string was checked for palindrome without using built-in functions. The program correctly identified whether the string is a palindrome or not.
