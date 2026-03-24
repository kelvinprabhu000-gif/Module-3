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
s = "google"

rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

## Output
<img width="685" height="525" alt="image" src="https://github.com/user-attachments/assets/9f3bbeab-4cd6-4a9e-8779-55dba1e21bd3" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome was executed successfully, and the output obtained
