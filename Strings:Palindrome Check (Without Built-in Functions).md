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
```
s = "google"
rev = s[::-1]

if s == rev:
    print(s, "is a palindrome")
else:
    print(s, "is not a palindrome")

```
Add code here

## Output
<img width="403" height="156" alt="image" src="https://github.com/user-attachments/assets/f16618b3-9d07-4d22-b957-67f92442e0d8" />

## Result
The program successfully checks whether the string "google" is a palindrome by manually reversing it and comparing with the original. In this case, it correctly identifies that "google" is not a palindrome
