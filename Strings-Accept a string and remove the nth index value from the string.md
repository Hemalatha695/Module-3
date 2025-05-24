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
Add Code Here
```
# Step 1: Define a function that removes the character at a given index
def remove(s):
    # Step 2: Read the index from the user
    n = int(input("Enter the index of the character to remove: "))
    
    # Step 3: Initialize an empty string to store the result
    a = ""
    
    # Step 4-6: Iterate and skip the character at index n
    for i in range(len(s)):
        if i != n:
            a += s[i]
    
    # Step 7: Return the modified string
    return a

# Get the string from the user
input_string = input("Enter a string: ")

# Step 8: Call the function and print the result
result = remove(input_string)
print("String after removing the character:", result)
```

## Output
![image](https://github.com/user-attachments/assets/4450c47e-bd3b-4449-9b62-89a10eee44d9)


## Result
This program successfully removes the character at the given index and returns the updated string
