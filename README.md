# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
list=[1,2,-8]
total=sum(list)
print(total)
```
## Output
![443557684-7dd5176d-6d7c-4e92-b93b-7908a1e68f96](https://github.com/user-attachments/assets/7dcc58dc-b624-46a3-824c-b81edfcf4770)

## Result
Thus,the program has been executed successfully.

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
```
import re
l1=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items:
   if not re.search(r"e",i):
      l1.append(i)
print(l1)
```
## Output
![443558263-e20ae089-3c58-4d0d-8ee1-c93dadf94222](https://github.com/user-attachments/assets/d095faa0-1ddc-4d11-97b8-6674f7d400cd)

## Result
Thus,the program has been executed successfully.

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
```

def remove(str):
  l=len(str)
a=""
n=int(input())
for i in range(0,l):
  if i==n:
    a=a+""
  else:
    a=a+str[i]
print(a)
```
## Output
![443559104-f1170fa2-e0e9-47fc-aeb4-9bc0fe79d627](https://github.com/user-attachments/assets/cc37ed40-343f-41e0-80b3-5b2c2d4bf667)

## Result
Thus,the program has been executed successfully.

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


string="google"
if string==string[::-1]:
   print ("The entered string is palindrome") 
else:
   print ("The entered string is not palindrome")
```
## Output
![443559703-19d2fc62-af1e-416b-bb1a-632152b94bf8](https://github.com/user-attachments/assets/13ca9c9b-7ebe-40c9-a40c-cd9eea21ec20)

## Result
Thus,the program has been executed successfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
tuplex = ("s", "8", "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in tuplex)
print("8" in tuplex)
```
## Output
![443560636-5c6097a5-3f2c-49eb-bea4-4a5d83819a80](https://github.com/user-attachments/assets/9f3d11a4-631d-484e-a77e-bc544ed8f7b6)

## Result
Thus,the program has been execueted successfully.
