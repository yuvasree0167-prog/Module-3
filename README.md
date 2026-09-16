# Module-3
#  Strings-Remove Nth Index Character from a String

##  Aim
To write a Python program that accepts a string and removes the character at a specified index.

##  Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

##  Program
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
<img width="766" height="173" alt="image" src="https://github.com/user-attachments/assets/3822d28b-5d3a-4673-b595-74f8fc380aaf" />


## Result
Thus the program has been successfully executed

# Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program
```
def is_palindrome_string(s):
    length = len(s)
    for i in range(length // 2):
        if s[i] != s[length - i -1]:
            return False
        return True
        
s = input()
if(is_palindrome_string(s)):
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```



## Output
<img width="1038" height="247" alt="image" src="https://github.com/user-attachments/assets/642ceb95-b50f-4b0a-ab1a-396c418903ec" />

# Regex in Python: Filter Words Without the Letter 'e'

##  Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

##  Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

##  Program
```
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result=[a for a in items if 'e' not in a]
print(result)
```
## Output
<img width="852" height="173" alt="image" src="https://github.com/user-attachments/assets/9961a11a-4390-45dc-8fda-8dfe0bdba330" />


## Result
The Python program was successfully executed to filter words from a list that do not contain the letter 'e' using regular expressions.

# List Operations in Python: Sum of List Items

##  Aim
To write a Python program that calculates the **sum of all elements** in a list.

##  Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

##  Program
```
lst1=[1,2,-8]
sum=0
for x in lst1:
    sum+=x
print(sum)
```


## Output
<img width="848" height="191" alt="image" src="https://github.com/user-attachments/assets/8d80cc6b-bfe6-4808-98c7-862a41065e10" />


## Result
The Python program was successfully executed to calculate the sum of all elements in a list.

# Tuple in Python: Check Element Existence

##  Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

##  Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

##  Program
```
tuplex = ("s", 3, "a", "e", "s", "o", "u", "r", "c", "e")
print("r" in tuplex)
print(5 in tuplex)
```
## Output
<img width="784" height="180" alt="image" src="https://github.com/user-attachments/assets/d3044e41-dd8c-448b-a824-ad438340bd09" />


## Result
The program successfully checks the existence of elements in the tuple.
## Result
The Python program was successfully executed to check whether a given string is a palindrome without using built-in palindrome functions
